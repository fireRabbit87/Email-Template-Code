## Reverse 2 Column Layout
Sometimes, a client will need a the image to be on the right and the text to be on the left...howver the still need the image to be the first thing a customer sees on a mobile device. 
```html
<tr>
  <td align="center">
    <table width="100%" cellspacing="0" cellpadding="0" border="0">
      <tr>
        <td align="center" style="padding:0 30px 30px 30px;" class="mobpad">
          <table cellspacing="0" cellpadding="0" border="0" width="100%">
            <tr>
              <td valign="top">
                <table cellspacing="0" cellpadding="0" border="0" align="right" width="305" class="container">
                  <tr>
                    <td align="center" valign="top" style="font-family:arial;font-size:20px;line-height:24px;color:#ffffff;font-weight:bold;" class="botpad">
                      <a href="#" target="_blank"><img alt="" src="http://placehold.it/610x400?text=Image Right" border="0" style="display:block;" width="305" height="200" class="photo"/></a>
                    </td>
                  </tr>
                </table>
                <table cellspacing="0" cellpadding="0" border="0" align="left" width="305" class="container">
                  <tr>
                    <td align="left" valign="top" style="font-family:arial;font-size:20px;line-height:24px; color:#000001;font-weight:bold;padding-bottom:15px;">
                      Heading
                    </td>
                  </tr>
                  <tr>
                    <td align="left" valign="top" style="font-family:arial;font-size:16px;line-height:22px;color:#000001;padding-bottom:15px;">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
                    </td>
                  </tr>
                </table>
              </td>
            </tr>
          </table>
        </td>
      </tr>
    </table>
  </td>
</tr>
```
Again, want a button on the text column? Look no further.
```html
<tr>
  <td align="center">
    <table width="100%" cellspacing="0" cellpadding="0" border="0">
      <tr>
        <td align="center" style="padding:0 30px 30px 30px;" class="mobpad">
          <table cellspacing="0" cellpadding="0" border="0" width="100%">
            <tr>
              <td valign="top">
                <table cellspacing="0" cellpadding="0" border="0" align="right" width="305" class="container">
                  <tr>
                    <td align="center" valign="top" style="font-family:arial;font-size:20px;line-height:24px;color:#ffffff;font-weight:bold;" class="botpad">
                      <a href="#" target="_blank"><img alt="" src="http://placehold.it/610x400?text=Image Right" border="0" style="display:block;" width="305" height="200" class="photo"/></a>
                    </td>
                  </tr>
                </table>
                <table cellspacing="0" cellpadding="0" border="0" align="left" width="305" class="container">
                  <tr>
                    <td align="left" valign="top" style="font-family:arial;font-size:20px;line-height:24px; color:#000001;font-weight:bold;padding-bottom:15px;">
                      Heading
                    </td>
                  </tr>
                  <tr>
                    <td align="left" valign="top" style="font-family:arial;font-size:16px;line-height:22px;color:#000001;padding-bottom:15px;">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
                    </td>
                  </tr>
                  <tr>
                    <td align="left">
                      <table cellspacing="0" cellpadding="0" border="0">
                        <tr>
                          <td align="left" style="font-family:arial;font-size:16px;line-height:22px;color:#ffffff;padding:10px 40px;border-radius:7px;-webkit-border-radius:7px;-moz-border-radius:7px;" bgcolor="#222222">
                            <a href="#" target="_blank" style="color:#FFFFFF;">CTA Button</a>
                          </td>
                        </tr>
                      </table>
                    </td>
                  </tr>
                </table>
              </td>
            </tr>
          </table>
        </td>
      </tr>
    </table>
  </td>
</tr>
```

Want the standard 2 column layout? [Check this out] (https://raw.githubusercontent.com/fireRabbit87/Email-Template-Code/master/2ColumnLayout.md)
