
<tbody>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">x264</span></p>
</td>
<td width="219">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td width="61">
<p align="left"><span lang="EN-US">ffmpeg</span></p>
</td>
<td width="250">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td width="182">
<p align="left"><span>说明</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span>命令行</span></p>
</td>
<td>
<p align="left"><span>字段</span></p>
</td>
<td>
<p align="left"><span>命令行</span></p>
</td>
<td>
<p align="left"><span>字段</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">qp</span></p>
<p align="left"><span lang="EN-US">qp_constant</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">cqp</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">cqp</span></p>
</td>
<td width="182">
<p align="left"><span>固定量化因子。取值范围<span lang="EN-US">0</span>到<span lang="EN-US">51</span>。</span></p>
<p align="left"><span>经常取值在<span lang="EN-US">20-40</span>之间，越小质量</span></p>
<p align="left"><span>越好<span lang="EN-US">,</span>要求的码率越高。<span lang="EN-US">0</span>表示无损压缩</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">max-keyint</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_keyint_max</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">g</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">gop_size</span></p>
</td>
<td width="182">
<p align="left"><span>关键帧的最大间隔帧数</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">min-keyint</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_keyint_min</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">keyint_min</span></p>
</td>
<td width="182">
<p align="left"><span>关键帧的最小间隔帧数</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">level</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_level_idc</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">level</span></p>
</td>
<td width="182">
<p align="left"><span>取值范围<span lang="EN-US">10-51</span>。</span></p>
<p align="left"><span>设置比特流的<span lang="EN-US">Level</span>。默认<span lang="EN-US">40</span>，即<span lang="EN-US">4.0</span>。</span></p>
<p align="left"><span>用来告诉解码器需要支持的什么级别的</span></p>
<p align="left"><span>兼容性。只有在你知道自己在做什么的</span></p>
<p align="left"><span>时候才设置该参数。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">frameref</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_frame_reference</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">refs</span></p>
</td>
<td width="182">
<p align="left"><span lang="EN-US">B</span><span>和<span lang="EN-US">P</span>帧向前预测参考的帧数。取值范</span></p>
<p align="left"><span>围<span lang="EN-US">1-16</span>。</span></p>
<p align="left"><span>该值不影响解码的速度，但是越大解码</span></p>
<p align="left"><span>所需的内存越大。这个值在一般情况下</span></p>
<p align="left"><span>越大效果越好，但是超过<span lang="EN-US">6</span>以后效果就</span></p>
<p align="left"><span>不明显了。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">bframes</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_bframe</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">max_b_frames</span></p>
</td>
<td width="182">
<p align="left"><span>最大<span lang="EN-US">B</span>帧数<span lang="EN-US">.</span></span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">b-adapt</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_bframe_adaptive</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_frame_strategy</span></p>
</td>
<td width="182">
<p align="left"><span>如果为<span lang="EN-US">true</span>，则自动决定什么时候需要</span></p>
<p align="left"><span>插入<span lang="EN-US">B</span>帧，最高达到设置的最大<span lang="EN-US">B</span>帧数。</span></p>
<p align="left"><span>如果设置为<span lang="EN-US">false,</span>那么最大的<span lang="EN-US">B</span>帧数被</span></p>
<p align="left"><span>使用。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">b-pyramid</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_bframe_pyramid</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS2(CODEC_FLAG2_BPYRAMID)</span></p>
</td>
<td width="182">
<p align="left"><span>当设置<span lang="EN-US">B</span>帧<span lang="EN-US">&gt;=2</span>时候，通过开启这个选</span></p>
<p align="left"><span>项可以获得质量的略微提高，但是没有</span></p>
<p align="left"><span>任何的速度损失。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_deblocking_filter</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS(CODEC_FLAG_LOOP_FILTER)</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">deblock</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_deblocking_filter_alphac0</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">deblockalpha</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">cabac</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_cabac</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">coder_type(FF_CODER_TYPE_AC)</span></p>
</td>
<td width="182">
<p align="left"><span>使用<span lang="EN-US">CABAC</span>熵编码技术<span lang="EN-US">,</span>为引起轻微的</span></p>
<p align="left"><span>编码和解码的速度损失，但是可以提高</span></p>
<p align="left"><span lang="EN-US">10%-15%</span><span>的编码质量。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">qmin</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_qp_min</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">qmin</span></p>
</td>
<td width="182">
<p align="left"><span>最小的量化因子。取值范围<span lang="EN-US">1-51</span>。建</span></p>
<p align="left"><span>议在<span lang="EN-US">10-30</span>之间。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">qmax</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_qp_max&nbsp;</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">qmax</span></p>
</td>
<td width="182">
<p align="left"><span>最大的量化因子。取值范围<span lang="EN-US">1-51</span>。建</span></p>
<p align="left"><span>议在<span lang="EN-US">10-30</span>之间。</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">qpstep</span></p>
<p align="left"><span lang="EN-US">qp-step</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_qp_step</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">max_qdiff</span></p>
</td>
<td width="182">
<p align="left"><span>最大的在帧与帧之间进行切变的量化</span></p>
<p align="left"><span>因子的变化量。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">qcomp</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">f_qcompress</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">vbv-maxrate</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_vbv_max_bitrate</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">rc_max_rate</span></p>
</td>
<td width="182">
<p align="left"><span>允许的最大码流<span lang="EN-US">,x264</span>里面以<span lang="EN-US">kbps</span>为</span></p>
<p align="left"><span>单位，<span lang="EN-US">ffmpeg</span>以<span lang="EN-US">bps</span>为单位</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">vbv-bufsize</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_vbv_buffer_size</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">bufsize</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">rc_buffer_size&nbsp;</span></p>
</td>
<td width="182">
<p align="left"><span>在指定<span lang="EN-US">vbv-maxrate</span>的时候必须设置</span></p>
<p align="left"><span>该字段。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">vbv-init</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">f_vbv_buffer_init</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">rc_initial_buffer_occupancy</span></p>
</td>
<td width="182">
<p align="left"><span>初始的缓存占用量</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">qcomp</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">f_qcompress</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">qcompress</span></p>
</td>
<td width="182">
<p align="left"><span>量化器压缩比率<span lang="EN-US">0-1.</span>越小则比特率</span></p>
<p align="left"><span>越区域固定，但是越高越使量化器</span></p>
<p align="left"><span>参数越固定。</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">direct-pred</span></p>
<p align="left"><span lang="EN-US">direct</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_direct_mv_pred</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">directpred</span></p>
</td>
<td width="182">
<p align="left"><span lang="EN-US">B</span><span>帧里面采用的运动侦测的方式。</span></p>
<p align="left"><span>时间和空间方式大致<span lang="EN-US">PSNR</span>和速度</span></p>
<p align="left"><span>是一致的。设置为<span lang="EN-US">auto</span>质量会好一</span></p>
<p align="left"><span>些，但是速度会下降一些，设置为<span lang="EN-US">0</span></span></p>
<p align="left"><span>，质量和速度都会下降<span lang="EN-US">.</span>可以选择</span></p>
<p align="left"><span lang="EN-US">none, auto, temporal, spatial.</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">weightb</span></p>
<p align="left"><span lang="EN-US">weight-b</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_weighted_bipred</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS2(CODEC_FLAG2_WPRED)</span></p>
</td>
<td width="182">
<p align="left"><span>当<span lang="EN-US">B</span>帧设置<span lang="EN-US">&gt;1</span>时使用</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">partitions</span></p>
<p align="left"><span lang="EN-US">analyse</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">inter</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td width="182">
<p align="left"><span lang="EN-US">X264_ANALYSE_I4x4</span></p>
<p align="left"><span lang="EN-US">X264_ANALYSE_I8x8</span></p>
<p align="left"><span lang="EN-US">X264_ANALYSE_PSUB16x16</span></p>
<p align="left"><span lang="EN-US">X264_ANALYSE_PSUB8x8</span></p>
<p align="left"><span lang="EN-US">X264_ANALYSE_BSUB16x16</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">8x8dct</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_transform_8x8</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS(CODEC_FLAG2_8X8DCT)</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">me</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_me_method</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">me_method</span></p>
</td>
<td width="182">
<p align="left"><span>运动侦测的方式</span></p>
<p align="left"><span lang="EN-US">ME_EPZS</span></p>
<p align="left"><span lang="EN-US">ME_HEX</span></p>
<p align="left"><span lang="EN-US">ME_UMH</span></p>
<p align="left"><span lang="EN-US">ME_FULL</span></p>
<p align="left"><span lang="EN-US">ME_ESA</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">me-range</span></p>
<p align="left"><span lang="EN-US">merange</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_me_range</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">me_range</span></p>
</td>
<td width="182">
<p align="left"><span>运动侦测的半径</span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">subq</span></p>
<p align="left"><span lang="EN-US">subme</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_subpel_refine</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">me_subpel_quality</span></p>
</td>
<td width="182">
<p align="left"><span>这个参数控制在运动估算过程中质</span></p>
<p align="left"><span>量和速度的权衡。<span lang="EN-US">Subq=5</span>可以压</span></p>
<p align="left"><span>缩<span lang="EN-US">&gt;10%</span>于<span lang="EN-US">subq=1</span>。<span lang="EN-US">1-7</span></span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">mixed-refs</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_mixed_references</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS2(CODEC_FLAG2_MIXED_REFS)</span></p>
</td>
<td width="182">
<p align="left"><span>允许<span lang="EN-US">8*8,16*8</span>运动块独立地选择</span></p>
<p align="left"><span>参考帧，如果<span lang="EN-US">disable,</span>则所有的宏</span></p>
<p align="left"><span>块必须参考同一帧。</span></p>
<p align="left"><span>需要<span lang="EN-US">frameref &gt; 1</span></span></p>
</td>
</tr>
<tr>
<td width="116">
<p align="left"><span lang="EN-US">brdo</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_bframe_rdo</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS2(CODEC_FLAG2_BRDO)</span></p>
</td>
<td width="182">
<p align="left"><span>需要<span lang="EN-US">subq&gt;6</span></span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">bime</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_bidir_me</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">bidir_refine</span></p>
</td>
<td width="182">
<p align="left"><span>取值范围：<span lang="EN-US">true,false.</span>这个值在没</span></p>
<p align="left"><span>有<span lang="EN-US">B</span>帧的时候失效。在双向预测宏块中</span></p>
<p align="left"><span>双向运动矢量使用。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">trellis</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_trellis</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">trellis</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">deadzone-intra</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_luma_deadzone</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>没有对应值</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">deadzone-inter</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_luma_deadzone</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>没有对应值</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">fast-pskip</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_fast_pskip</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS(CODEC_FLAG2_FASTPSKIP)</span></p>
</td>
<td width="182">
<p align="left"><span>在<span lang="EN-US">P</span>帧内执行早期快速跳跃探测。</span></p>
<p align="left"><span>这个经常在没有任何损失的前提</span></p>
<p align="left"><span>下提高了速度。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">dct-decimate</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_dct_decimate</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>没有对应值</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">nr</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_noise_reduction</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">noise_reduction</span></p>
</td>
<td width="182">
<p align="left"><span lang="EN-US">0</span><span>意味着关闭，对于噪声很大的</span></p>
<p align="left"><span>内容你需要打开。</span></p>
<p align="left"><span>范围：<span lang="EN-US">0-100000</span></span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">interlaced</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_interlaced</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>没有对应值</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">global-header</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_repeat_headers</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS(CODEC_FLAG_GLOBAL_HEADER)</span></p>
</td>
<td width="182">
<p align="left"><span>使得<span lang="EN-US">SPS</span>和<span lang="EN-US">PPS</span>只在流的开始处</span></p>
<p align="left"><span>产生一次。有些播放器，如<span lang="EN-US">SONY</span></span></p>
<p align="left"><span>的<span lang="EN-US">PSP</span>需要开启此参数。默认的设</span></p>
<p align="left"><span>置使得<span lang="EN-US">SPS</span>和<span lang="EN-US">PPS</span>在每一个<span lang="EN-US">IDR</span>帧</span></p>
<p align="left"><span>开始出都进行重复。</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">aud</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_aud</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS2(CODEC_FLAG2_AUD)</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">threads</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_threads</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">thread_count</span></p>
</td>
<td width="182">
<p align="left"><span>将帧切分成块，由不同的线程进行</span></p>
<p align="left"><span>分别编码。<span lang="EN-US">0-4</span>。</span></p>
<p align="left"><span lang="EN-US">0 for auto</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">rc-eq</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">psz_rc_eq</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">rc_eq</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">--no-psnr</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_psnr</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">FLAGS(CODEC_FLAG_PSNR)</span></p>
</td>
<td width="182">
<p align="left"><span>是否开启<span lang="EN-US">PSNR.</span></span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">--no-ssim</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_ssim</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>没有对应值</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">--progress</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b_progress</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span>没有对应值</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">--bitrate</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">i_bitrate</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">b</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">bit_rate</span></p>
</td>
<td width="182">
<p align="left"><span>编码输出的比特率<span lang="EN-US">,</span>并启用</span></p>
<p align="left"><span lang="EN-US">ABR(Average Birtate&nbsp;</span><span>模式（<span lang="EN-US">i_rc_method),</span></span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span lang="EN-US">qblur</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">f_qblur</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">qblur</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
<tr>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">f_complexity_blur</span></p>
</td>
<td>
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
<td>
<p align="left"><span lang="EN-US">complexityblur</span></p>
</td>
<td width="182">
<p align="left"><span>　</span></p>
<p align="left"><span lang="EN-US">&nbsp;</span></p>
</td>
</tr>
</tbody>
