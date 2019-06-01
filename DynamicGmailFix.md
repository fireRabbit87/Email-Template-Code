## Gmail Fix

This is so that in Gmail, so that it adjusts the full width of the email. The example below is for a template width of 700 pixels.

```html
<tr>
  <td align="center" class="mobhide">
    <table width="100%" cellspacing="0" cellpadding="0" border="0" bgcolor="#ffffff">
     <tr>
       <td style="line-height:1px"><img alt="" src="http://image.exct.net/lib/fe641570776d02757515/m/1/spacer_1px_transparent.gif" width="140" height="1" border="0" style="display:block;"/></td>
       <td style="line-height:1px"><img alt="" src="http://image.exct.net/lib/fe641570776d02757515/m/1/spacer_1px_transparent.gif" width="140" height="1" border="0" style="display:block;"/></td>
       <td style="line-height:1px"><img alt="" src="http://image.exct.net/lib/fe641570776d02757515/m/1/spacer_1px_transparent.gif" width="140" height="1" border="0" style="display:block;"/></td>
       <td style="line-height:1px"><img alt="" src="http://image.exct.net/lib/fe641570776d02757515/m/1/spacer_1px_transparent.gif" width="140" height="1" border="0" style="display:block;"/></td>
       <td style="line-height:1px"><img alt="" src="http://image.exct.net/lib/fe641570776d02757515/m/1/spacer_1px_transparent.gif" width="140" height="1" border="0" style="display:block;"/></td>
     </tr>
    </table>
  </td>
</tr>
```

All that's required is to divide the full width by 5. For example, if the width of the email is 600 pixels wide, then after dividing by 5 the width of each table cell (<td>) 140 pixels for each cell.
