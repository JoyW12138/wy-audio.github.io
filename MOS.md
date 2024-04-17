---
title: A Two-Stage Approach to Quality Restoration of Bone-Conducted Speech
tags: 
 - Bone-conducted Speech Enhancement
 - Deep Neural Network
categories: Speech Enhancement
---
Author: Changtao Li
Email: lichangtao@mail.ioa.ac.cn

根据以下示例，对音频文件进行打分
<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td></td>  
      <td> 1分音频示例 <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_1/bc_0.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> 5分音频示例 <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_1/ac_0.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td></td>     
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_13/bc_22.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_13/ac_22.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample3</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_17/sample_18.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_17/sample_18.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_17/sample_18.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_17/sample_18.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_17/sample_18.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_17/sample_18.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_17/sample_18.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_17/bc_18.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_17/ac_18.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample4</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_19/sample_13.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_19/sample_13.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_19/sample_13.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_19/sample_13.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_19/sample_13.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_19/sample_13.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_19/sample_13.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_19/bc_13.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_19/ac_13.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample5</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_22/sample_16.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_22/sample_16.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_22/sample_16.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_22/sample_16.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_22/sample_16.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_22/sample_16.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_22/sample_16.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_22/bc_16.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_22/ac_16.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample6</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_3/sample_1.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_3/sample_1.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_3/sample_1.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_3/sample_1.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_3/sample_1.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_3/sample_1.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_3/sample_1.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_3/bc_1.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_3/ac_1.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample7</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_1/sample_1.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_1/sample_1.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_1/sample_1.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_1/sample_1.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_1/sample_1.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_1/sample_1.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_1/sample_1.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_1/bc_1.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_1/ac_1.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample8</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_13/sample_24.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_13/sample_24.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_13/sample_24.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_13/sample_24.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_13/sample_24.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_13/sample_24.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_13/sample_24.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_13/bc_24.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_13/ac_24.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample9</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_17/sample_41.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_17/sample_41.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_17/sample_41.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_17/sample_41.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_17/sample_41.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_17/sample_41.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_17/sample_41.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_17/bc_41.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_17/ac_41.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample10</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_19/sample_20.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_19/sample_20.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_19/sample_20.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_19/sample_20.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_19/sample_20.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_19/sample_20.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_19/sample_20.wav" controls></td>      
      <<td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_19/bc_20.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_19/ac_20.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample11</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_22/sample_22.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_22/sample_22.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_22/sample_22.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_22/sample_22.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_22/sample_22.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_22/sample_22.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_22/sample_22.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_22/bc_22.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_22/ac_22.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample12</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_3/sample_12.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_3/sample_12.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_3/sample_12.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_3/sample_12.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_3/sample_12.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_3/sample_12.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_3/sample_12.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_3/bc_12.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_3/ac_12.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample13</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_1/sample_15.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_1/sample_15.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_1/sample_15.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_1/sample_15.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_1/sample_15.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_1/sample_15.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_1/sample_15.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_1/bc_15.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_1/ac_15.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample14</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_13/sample_27.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_13/sample_27.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_13/sample_27.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_13/sample_27.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_13/sample_27.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_13/sample_27.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_13/sample_27.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_13/bc_27.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_13/ac_27.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample15</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_17/sample_5.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_17/sample_5.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_17/sample_5.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_17/sample_5.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_17/sample_5.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_17/sample_5.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_17/sample_5.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_17/bc_5.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_17/ac_5.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample16</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_19/sample_21.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_19/sample_21.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_19/sample_21.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_19/sample_21.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_19/sample_21.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_19/sample_21.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_19/sample_21.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_19/bc_21.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_19/ac_21.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample17</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_22/sample_3.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_22/sample_3.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_22/sample_3.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_22/sample_3.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_22/sample_3.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_22/sample_3.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_22/sample_3.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_22/bc_3.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_22/ac_3.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample18</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_3/sample_22.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_3/sample_22.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_3/sample_22.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_3/sample_22.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_3/sample_22.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_3/sample_22.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_3/sample_22.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_3/bc_22.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_3/ac_22.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample19</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_1/sample_22.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_1/sample_22.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_1/sample_22.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_1/sample_22.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_1/sample_22.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_1/sample_22.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_1/sample_22.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_1/bc_22.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_1/ac_22.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample20</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_13/sample_35.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_13/sample_35.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_13/sample_35.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_13/sample_35.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_13/sample_35.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_13/sample_35.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_13/sample_35.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_13/bc_35.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_13/ac_35.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample21</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_17/sample_51.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_17/sample_51.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_17/sample_51.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_17/sample_51.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_17/sample_51.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_17/sample_51.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_17/sample_51.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_17/bc_51.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_17/ac_51.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample22</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_19/sample_24.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_19/sample_24.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_19/sample_24.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_19/sample_24.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_19/sample_24.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_19/sample_24.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_19/sample_24.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_19/bc_24.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_19/ac_24.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample23</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_22/sample_31.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_22/sample_31.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_22/sample_31.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_22/sample_31.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_22/sample_31.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_22/sample_31.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_22/sample_31.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_22/bc_31.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_22/ac_31.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample24</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_3/sample_26.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_3/sample_26.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_3/sample_26.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_3/sample_26.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_3/sample_26.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_3/sample_26.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_3/sample_26.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_3/bc_26.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_3/ac_26.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample25</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_1/sample_23.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_1/sample_23.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_1/sample_23.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_1/sample_23.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_1/sample_23.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_1/sample_23.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_1/sample_23.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_1/bc_23.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_1/ac_23.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample26</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_13/sample_36.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_13/sample_36.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_13/sample_36.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_13/sample_36.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_13/sample_36.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_13/sample_36.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_13/sample_36.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_13/bc_36.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_13/ac_36.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample27</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_17/sample_53.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_17/sample_53.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_17/sample_53.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_17/sample_53.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_17/sample_53.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_17/sample_53.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_17/sample_53.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_17/bc_53.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_17/ac_53.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample28</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_19/sample_28.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_19/sample_28.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_19/sample_28.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_19/sample_28.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_19/sample_28.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_19/sample_28.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_19/sample_28.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_19/bc_28.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_19/ac_28.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample29</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_22/sample_32.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_22/sample_32.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_22/sample_32.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_22/sample_32.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_22/sample_32.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_22/sample_32.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_22/sample_32.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_22/bc_32.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_22/ac_32.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>

<table>
  <tbody>
    <tr>
    </tr>
    <tr>
      <td>Sample30</td>
      <td> DCCRN-AF <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_-10/speaker_3/sample_27.wav" controls></td>
      <td> DCCRN-BC <audio src="https://github.com/changtaoli/samples/raw/main/dccrn_stft/speaker_3/sample_27.wav" controls></td>
      <td> S2 <audio src="https://github.com/changtaoli/samples/raw/main/direct/speaker_3/sample_27.wav" controls></td>
      <td> DPT-EGNet <audio src="https://github.com/changtaoli/samples/raw/main/dpt/speaker_3/sample_27.wav" controls></td>
    </tr>
    <tr>
      <td></td>
      <td> Proposed <audio src="https://github.com/changtaoli/samples/raw/main/ours/speaker_3/sample_27.wav" controls></td>
      <td> S1 <audio src="https://github.com/changtaoli/samples/raw/main/unet_stft/speaker_3/sample_27.wav" controls></td>
      <td> WaveNet <audio src="https://github.com/changtaoli/samples/raw/main/wavenet_-10/speaker_3/sample_27.wav" controls></td>      
      <td> BC <audio src="https://github.com/changtaoli/samples/raw/main/bc/speaker_3/bc_27.wav" controls></td>    
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td> AC <audio src="https://github.com/changtaoli/samples/raw/main/ac/speaker_3/ac_27.wav" controls></td>
      <td></td>
    </tr>
  </tbody>
  <colgroup>
  </colgroup>
</table>
