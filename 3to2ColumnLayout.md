## 3 to 2 Column Layout

This layout is to turn a three column layout on desktop to a 2 column layout on mobile devices.

```html
<tr>
  <td align="center" valign="top" width="100%">
    <table class="container" id="content-table" width="600" cellpadding="0" cellspacing="0" border="0" style="min-width:320px;">
      <tr>
        <td style="padding-bottom:15px;">
          <table cellspacing="0" cellpadding="0" border="0" width="200" align="left" class="container50">
            <tr>
              <td align="left" valign="top" width="300" class="drop" bgcolor="blue" height="100">
                box 1
              </td>
            </tr>
          </table>
          <!--[if (gte mso 9)|(IE)]>
        </td>
        <td valign="top">
          <![endif]-->
          <table cellspacing="0" cellpadding="0" border="0" width="200" align="left" class="container50">
            <tr>
              <td align="left" valign="top" width="300" class="drop" bgcolor="red" height="100">
                box 2
              </td>
            </tr>
          </table>
          <!--[if (gte mso 9)|(IE)]>
        </td>
        <td valign="top">
          <![endif]-->
          <table cellspacing="0" cellpadding="0" border="0" width="200" align="left" class="container50">
            <tr>
              <td align="left" valign="top" width="300" class="drop" bgcolor="green" height="100">
                box 3
              </td>
            </tr>
          </table>
          <!--[if (gte mso 9)|(IE)]>
        </td>
      </tr>
      <tr>
        <td valign="top">
          <![endif]-->
          <table cellspacing="0" cellpadding="0" border="0" width="200" align="left" class="container50">
            <tr>
              <td align="left" valign="top" width="300" class="drop" bgcolor="blue" height="100">
                box 4
              </td>
            </tr>
          </table>
          <!--[if (gte mso 9)|(IE)]>
        </td>
        <td valign="top">
          <![endif]-->
          <table cellspacing="0" cellpadding="0" border="0" width="200" align="left" class="container50">
            <tr>
              <td align="left" valign="top" width="300" class="drop" bgcolor="red" height="100">
                box 5
              </td>
            </tr>
          </table>
          <!--[if (gte mso 9)|(IE)]>
        </td>
        <td valign="top">
          <![endif]-->
          <table cellspacing="0" cellpadding="0" border="0" width="200" align="left" class="container50">
            <tr>
              <td align="left" valign="top" width="300" class="drop" bgcolor="green" height="100">
                box 6
              </td>
            </tr>
          </table>
        </td>
      </tr>
    </table>
  </td>
</tr>
```
 
