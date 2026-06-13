# h4nszizworks-dot.github.io


<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SOCA Form</title>

<style>

body{
    font-family: Arial, sans-serif;
    background:#f0f0f0;
    padding:20px;
}

.container{
    max-width:900px;
    margin:auto;
    background:white;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

table{
    width:100%;
    border-collapse:collapse;
}

td{
    border:1px solid #000;
    padding:5px;
    vertical-align:top;
}

.header{
    text-align:center;
    font-weight:bold;
}

.title{
    font-size:24px;
}

.subtitle{
    font-size:20px;
}

input[type=text],
input[type=date],
textarea{
    width:100%;
    border:none;
    outline:none;
    resize:vertical;
    font-size:14px;
    box-sizing:border-box;
}

.obs-box{
    min-height:140px;
}

.response-box{
    min-height:120px;
}

.recommend-box{
    min-height:120px;
}

.signature-box{
    min-height:80px;
}

.blue{
    color:#3366cc;
    font-style:italic;
}

.checkbox-row{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.submit-btn{
    width:100%;
    padding:15px;
    margin-top:15px;
    background:#004080;
    color:white;
    border:none;
    cursor:pointer;
    font-size:16px;
}

.submit-btn:hover{
    background:#00264d;
}

@media(max-width:768px){

    .checkbox-row{
        flex-direction:column;
        align-items:flex-start;
        gap:5px;
    }

}

</style>
</head>

<body>

<div class="container">

<form action="https://formspree.io/f/mjgdpddj"
      method="POST">

<input type="hidden"
       name="_subject"
       value="SOCA Report PT Taka Geodrill Indonesia">

<table>

<tr>
<td colspan="2" class="header title">
PT TAKA GEODRILL INDONESIA
</td>
</tr>

<tr>
<td colspan="2" class="header subtitle">
SOCA (SAFETY OBSERVATION CARD)
</td>
</tr>

<tr>

<td width="50%">
<b>Departemen</b> /
<span class="blue">Department</span> :

<br><br>

<input type="text" name="department">
</td>

<td width="50%">
<b>Lokasi</b> /
<span class="blue">Location</span> :

<br><br>

<input type="text" name="location">
</td>

</tr>

<tr>

<td>

<div class="checkbox-row">

<div>
Perbuatan Tidak Aman /
<span class="blue">Unsafe Action</span>
</div>

<input type="checkbox"
       name="observation_type[]"
       value="Unsafe Action">

</div>

</td>

<td>

<div class="checkbox-row">

<div>
Perbuatan Aman /
<span class="blue">Safe Action</span>
</div>

<input type="checkbox"
       name="observation_type[]"
       value="Safe Action">

</div>

</td>

</tr>

<tr>

<td>

<div class="checkbox-row">

<div>
Kondisi Tidak Aman /
<span class="blue">Unsafe Condition</span>
</div>

<input type="checkbox"
       name="observation_type[]"
       value="Unsafe Condition">

</div>

</td>

<td>

<div class="checkbox-row">

<div>
Kondisi Aman /
<span class="blue">Safe Condition</span>
</div>

<input type="checkbox"
       name="observation_type[]"
       value="Safe Condition">

</div>

</td>

</tr>

<tr>

<td colspan="2">

<b>Observasi</b> /
<span class="blue">Observation</span> :

<br><br>

<textarea
class="obs-box"
name="observation"></textarea>

</td>

</tr>

<tr>

<td colspan="2">

<b>Tindakan Perbaikan Segera</b> /
<span class="blue">Immediate Response</span>

(Untuk Situasi Tidak Aman)

<br><br>

<textarea
class="response-box"
name="immediate_response"></textarea>

</td>

</tr>

<tr>

<td colspan="2">

<b>Rekomendasi dan Observasi Anda</b> /
<span class="blue">
Your Recommendations and Observation
</span>

<br><br>

<textarea
class="recommend-box"
name="recommendation"></textarea>

</td>

</tr>

<tr>

<td colspan="2">

<b>Nama, Tanda Tangan dan Tanggal</b> /
<span class="blue">
Name, Signature and Date
</span>

<br><br>

<input type="text"
       name="name_signature_date">

</td>

</tr>

<tr>

<td colspan="2"
style="text-align:right">

FM/TGI/QHSE-028 Rev 00

</td>

</tr>

</table>

<button type="submit" class="submit-btn">
SUBMIT SOCA REPORT
</button>

</form>

</div>

</body>
</html>



