<div class="post-body post-content">
<style> 
table tr td{
  border:1px solid #CCCCCC;border-width: 1px;padding:5px;
}
table input,table form,table textarea,table button {-webkit-appearance: auto;  -moz-appearance: auto; appearance: auto;}
.accbutton{
-webkit-border-radius: 5px;
-moz-border-radius: 5px;
border-radius: 5px;
-webkit-box-shadow: rgba(0,0,0,1) 0 1px 0;
-moz-box-shadow: rgba(0,0,0,1) 0 1px 0;
box-shadow: rgba(0,0,0,1) 0 1px 0;
padding: 4px 7px;
width: 170px;
clear: none;
display: block;
text-decoration: none;
margin: auto;
height: 35px;
line-height: 23px;
text-align: center;
font-weight: bold;
cursor: pointer; 
}
input {
max-width:110px;
}
</style>
<table class="contentpaneopen" style="width:100%;border-spacing: 0;">
<tbody>
<tr>
<td valign="top">

<div id="calc">
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;padding: 1px;">
<tbody>
<tr>
<td>
<form id="f">
<table border="0" style="width: 100%;font-size: 13px;">
<label id="error" style="border:2px solid red; display:none; font-size:12px;"></label>
<tbody>
<tr>
<td width="45%">High price:</td>
<td width="55%"><input class="f2" id="H" name="H" type="text"/></td>
</tr>
<tr>
<td>Low price:</td>
<td><input class="f2" id="L" name="L" type="text"/></td>
</tr>
<tr>
<td>Close price:</td>
<td><input class="f2" id="C" name="C" type="text"/></td>
</tr>
<tr>
<td>Current Open price:<sup>*</sup></td>
<td><input class="f2" id="O" name="O" type="text"/></td>
</tr>
<tr>
<td><input class="f2 accbutton" onclick="CalcPP();" type="button" value="Calculate"/></td>
</tr>
<tr>
<td><span><sup>*</sup> For DeMark's pivot points.</span></td>
</tr>
</tbody>
</table>
</form>
<h4>Results:</h4>
<table border="0" cellpadding="0" cellspacing="2" style="font-size: 12px;width: 100%;">
<tbody>
<tr>
<td width="20%"> </td>
<td align="center" width="12%"><strong>Floor Pivot Pts</strong></td>
<td align="center" width="12%"><strong>Woodie's Pivot Pts</strong></td>
<td align="center" width="12%"><strong>Camarilla Pivot Pts</strong></td>
<td align="center" width="12%"><strong>DeMark's Pivot Pts</strong></td>
</tr>
</tbody>
</table>
<form id="f2">
<table border="0" cellpadding="0" cellspacing="2" style="font-size: 12px;width: 100%;">
<tbody>
<tr>
<td width="20%">4th Resistance =</td>
<td align="center" width="12%"><input type="text"/></td>
<td width="12%"><input type="text"/></td>
<td align="center" width="12%"><input class="f2" id="r4c" name="r4c" type="text"/></td>
<td width="12%"><input type="text"/></td>
</tr>
<tr>
<td>3rd Resistance =</td>
<td align="center"><input class="f2" id="r31" name="r31" type="text"/></td>
<td><input type="text"/></td>
<td align="center"><input class="f2" id="r3c" name="r3c" type="text"/></td>
<td><input type="text"/></td>
</tr>
<tr>
<td>2nd Resistance =</td>
<td align="center"><input class="f2" id="r21" name="r21" type="text"/></td>
<td align="center"><input class="f2" id="r22" name="r22" type="text"/></td>
<td align="center"><input class="f2" id="r2c" name="r2c" type="text"/></td>
<td><input type="text"/></td>
</tr>
<tr>
<td>1st Resistance =</td>
<td align="center"><input class="f2" id="r11" name="r11" type="text"/></td>
<td align="center"><input class="f2" id="r12" name="r12" type="text"/></td>
<td align="center"><input class="f2" id="r1c" name="r1c" type="text"/></td>
<td align="center"><input class="f2" id="h1" name="h1" type="text"/></td>
</tr>
<tr>
<td>Pivot Point =</td>
<td align="center"><input class="f2" id="p1" name="p1" type="text"/></td>
<td align="center"><input class="f2" id="p2" name="p2" type="text"/></td>
<td><input type="text"/></td>
<td><input type="text"/></td>
</tr>
<tr>
<td>1st Support =</td>
<td align="center"><input class="f2" id="data11" name="data11" type="text"/></td>
<td align="center"><input class="f2" id="data12" name="data12" type="text"/></td>
<td align="center"><input class="f2" id="s1c" name="s1c" type="text"/></td>
<td align="center"><input class="f2" id="l1" name="l1" type="text"/></td>
</tr>
<tr>
<td>2nd Support =</td>
<td align="center"><input class="f2" id="data21" name="data21" type="text"/></td>
<td align="center"><input class="f2" id="data22" name="data22" type="text"/></td>
<td align="center"><input class="f2" id="s2c" name="s2c" type="text"/></td>
<td><input type="text"/></td>
</tr>
<tr>
<td>3rd Support =</td>
<td align="center"><input class="f2" id="s31" name="s31" type="text"/></td>
<td><input type="text"/></td>
<td align="center"><input class="f2" id="s3c" name="s3c" type="text"/></td>
<td><input type="text"/></td>
</tr>
<tr>
<td>4th Support =</td>
<td><input type="text"/></td>
<td><input type="text"/></td>
<td align="center"><input class="f2" id="s4c" name="s4c" type="text"/></td>
<td><input type="text"/></td>
</tr>
</tbody>
</table>
</form>
</td>
</tr>
</tbody>
</table>
</div>
</td>
</tr>
</tbody>
</table>



</div>