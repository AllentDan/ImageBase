<head>
  <style type="text/css">
  .tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;}
  .tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
    font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
  .tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
    font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
  .tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
  .tg .tg-kyy7{background-color:#f9f9f9;border-color:inherit;text-align:center;vertical-align:middle}
  </style>
  <table class="tg">
  <thead>
    <tr>
      <th class="tg-9wq8">Model</th>
      <th class="tg-9wq8">Config</th>
      <th class="tg-9wq8">Dataset</th>
      <th class="tg-9wq8">Metric</th>
      <th class="tg-9wq8">PyTorch</th>
      <th class="tg-9wq8">ONNX Runtime</th>
      <th class="tg-9wq8">TensorRT-FP32</th>
      <th class="tg-9wq8">TensorRT-FP16</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-kyy7" rowspan="6">ESRGAN</td>
      <td class="tg-kyy7" rowspan="6">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;esrgan_x4c64b23g32_g1_400k_div2k.py&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
      <td class="tg-kyy7" rowspan="2">Set5</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">28.2700</td>
      <td class="tg-kyy7">28.2619</td>
      <td class="tg-kyy7">28.2619</td>
      <td class="tg-kyy7">28.2616</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.7778</td>
      <td class="tg-9wq8">0.7784</td>
      <td class="tg-9wq8">0.7784</td>
      <td class="tg-9wq8">0.7783</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="2">Set14</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">24.6328</td>
      <td class="tg-kyy7">24.6290</td>
      <td class="tg-kyy7">24.6290</td>
      <td class="tg-kyy7">24.6274</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.6491</td>
      <td class="tg-9wq8">0.6494</td>
      <td class="tg-9wq8">0.6494</td>
      <td class="tg-9wq8">0.6494</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="2">DIV2K</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">26.6531</td>
      <td class="tg-kyy7">26.6532</td>
      <td class="tg-kyy7">26.6532</td>
      <td class="tg-kyy7">26.6532</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.7340</td>
      <td class="tg-9wq8">0.7340</td>
      <td class="tg-9wq8">0.7340</td>
      <td class="tg-9wq8">0.7340</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="6">ESRGAN</td>
      <td class="tg-kyy7" rowspan="6">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;esrgan_psnr_x4c64b23g32_g1_1000k_div2k.py&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
      <td class="tg-kyy7" rowspan="2">Set5</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">30.6428</td>
      <td class="tg-kyy7">30.6307</td>
      <td class="tg-kyy7">30.6307</td>
      <td class="tg-kyy7">30.6305</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.8559</td>
      <td class="tg-9wq8">0.8565</td>
      <td class="tg-9wq8">0.8565</td>
      <td class="tg-9wq8">0.8566</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="2">Set14</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">27.0543</td>
      <td class="tg-kyy7">27.0422</td>
      <td class="tg-kyy7">27.0422</td>
      <td class="tg-kyy7">27.0411</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.7447</td>
      <td class="tg-9wq8">0.7450</td>
      <td class="tg-9wq8">0.7450</td>
      <td class="tg-9wq8">0.7449</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="2">DIV2K</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">29.3354</td>
      <td class="tg-kyy7">29.3354</td>
      <td class="tg-kyy7">29.3354</td>
      <td class="tg-kyy7">29.3339</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.8263</td>
      <td class="tg-9wq8">0.8263</td>
      <td class="tg-9wq8">0.8263</td>
      <td class="tg-9wq8">0.8263</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="6">SRCNN</td>
      <td class="tg-kyy7" rowspan="6">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;srcnn_x4k915_g1_1000k_div2k.py&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
      <td class="tg-kyy7" rowspan="2">Set5</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">28.4316</td>
      <td class="tg-kyy7">28.4120</td>
      <td class="tg-kyy7">27.2144</td>
      <td class="tg-kyy7">27.2127</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.8099</td>
      <td class="tg-9wq8">0.8106</td>
      <td class="tg-9wq8">0.7782</td>
      <td class="tg-9wq8">0.7781</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="2">Set14</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">25.6486</td>
      <td class="tg-kyy7">25.6367</td>
      <td class="tg-kyy7">24.8613</td>
      <td class="tg-kyy7">24.8599</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.7014</td>
      <td class="tg-9wq8">0.7015</td>
      <td class="tg-9wq8">0.6674</td>
      <td class="tg-9wq8">0.6673</td>
    </tr>
    <tr>
      <td class="tg-kyy7" rowspan="2">DIV2K</td>
      <td class="tg-kyy7">PSNR</td>
      <td class="tg-kyy7">27.7460</td>
      <td class="tg-kyy7">27.7460</td>
      <td class="tg-kyy7">26.9891</td>
      <td class="tg-kyy7">26.9862</td>
    </tr>
    <tr>
      <td class="tg-9wq8">SSIM</td>
      <td class="tg-9wq8">0.7854</td>
      <td class="tg-9wq8">0.7854</td>
      <td class="tg-9wq8">0.7605</td>
      <td class="tg-9wq8">0.7604</td>
    </tr>
  </tbody>
  </table>
</head>
