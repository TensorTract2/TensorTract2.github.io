<div style="text-align: center;">
<h2><b>Precisely Controllable Neural Speech Synthesis</b></h2>
<p> Submitted to </p>
<p> Code and model weights will be published on paper acceptance </p>
</div>


<br>
<div style="text-align: center;">
<a id="audio_examples">
</a>
<div style="text-align: center;">
<h2>Deep Articulatory Synthesis</h2>
</div>

<b>English Speech Synthesis:</b> The following samples were randomly selected from the LibriTTS-R test-clean set and re-synthesized using the proposed method.

<table border="1">
<tr><td>Speaker</td><td colspan="2"> <b>LibriTTS-R</b> </td></tr>
<tr>
  <td></td>
  <td>Ground Truth</td>
  <td>Re-synthesis</td>
</tr>

<tr><td>260</td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_gt_260_54_8.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_rs_260_54_8.wav"></audio></td>
</tr>

<tr><td>4446</td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_gt_4446_0_7.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_rs_4446_0_7.wav"></audio></td>
</tr>

<tr><td>5683</td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_gt_5683_66_52.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_rs_5683_66_52.wav"></audio></td>
</tr>

<tr><td>7021</td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_gt_7021_14_2.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_rs_7021_14_2.wav"></audio></td>
</tr>

<tr><td>8455</td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_gt_8455_40_14.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/lttsr_rs_8455_40_14.wav"></audio></td>
</tr>

</table>

<br>
<b>Mulitlingual Speech Synthesis:</b> The following samples were randomly selected from theMulitlingual Librispeech (MLS) test sets and re-synthesized using the proposed method.

<table border="1">
<tr><td>Language</td><td colspan="2"> <b>Multilingual Librispeech</b> </td></tr>
<tr>
  <td></td>
  <td>Ground Truth</td>
  <td>Re-synthesis</td>
</tr>

<tr><td>German</td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_de_gt_3040_74_6.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_de_rs_3040_74_6.wav"></audio></td>
</tr>

<tr><td>Dutch</td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_nl_gt_3775_0.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_nl_rs_3775_0.wav"></audio></td>
</tr>

<tr><td>French</td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_fr_gt_2695_3.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_fr_rs_2695_3.wav"></audio></td>
</tr>

<tr><td>Spanish</td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_es_gt_2255_0.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_es_rs_2255_0.wav"></audio></td>
</tr>

<tr><td>Italian</td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_it_gt_644_0.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_it_rs_644_0.wav"></audio></td>
</tr>

<tr><td>Portuguese</td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_pt_gt_412_0.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_pt_rs_412_0.wav"></audio></td>
</tr>

<tr><td>Polish</td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_pl_gt_14_12.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/mls_pl_rs_14_12.wav"></audio></td>
</tr>

</table>


<div style="text-align: center;">
<h2>Controllability of Deep Articulatory Synthesis</h2>
</div>

Controllability


<div style="text-align: center;">
<h2>Articulatory Synthesis</h2>
</div>
The following German speech samples were encoded using the proposed method and then re-synthesized using the articulatory synthesizer VocalTractLab.

<table border="1">
<tr><td>Speaker</td><td colspan="2"> <b>Kiel Dataset</b> </td></tr>
<tr>
  <td></td>
  <td>Ground Truth</td>
  <td>VTL (Rule-based)</td>
  <td>TensorTract2</td>
</tr>

<tr><td></td>
  <td><audio controls style="width: 110px;" src="audio_examples/as_gt_b_0_2.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/as_vtl_b_0_2.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/as_tt2_b_0_2.wav"></audio></td>
</tr>

<tr><td></td>
  <td><audio controls style="width: 110px;" src="audio_examples/as_gt_b_0_26.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/as_vtl_b_0_26.wav"></audio></td>
  <td><audio controls style="width: 110px;" src="audio_examples/as_tt2_b_0_26.wav"></audio></td>
</tr>

</table>