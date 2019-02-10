## Hamburger Menu

This will allow you to create a hamburger menu, just like youw would see on a normal website.Typically used for when you have a menu in a email. Instead of hiding the menu, you can use this to display it without doing any fancy show/hide functionality.

```html
<table width="100%" cellspacing="0" cellpadding="0" border="0" bgcolor="#ffffff">
  <tr>
    <td align="center" valign="bottom" style="padding:15px 30px 15px 30px;">
      <table width="100%" cellspacing="0" cellpadding="0" border="0">
        <tr>
          <td align="left">
            <table cellspacing="0" cellpadding="0" border="0" class="container">
              <tr>
                <!--[if mso]>
                <td valign="top">
                <![endif]-->
                <label for="mobile-checkbox" id="mobile-label" style="display: none;"> <b></b><b></b><b></b> </label>
                <!--[if mso]>
                </td>
                <![endif]--> 
              </tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>
 ```

Here's the code to show your menu within the email.
```html
<table width="100%" cellspacing="0" cellpadding="0" border="0" bgcolor="#ffffff">
  <tr>
    <td align="center" valign="bottom" style="padding:15px 30px 15px 30px;">
      <table style="table-layout: fixed;" width="100%" cellspacing="0" cellpadding="0" border="0" bgcolor="#000001">
        <tbody>
          <tr>
            <td valign="top" align="center">
              <!--[if mso]>
              <p style="display: none;">
              <![endif]-->
              <input id="mobile-checkbox" style="max-height: 0px; visibility: hidden; overflow: hidden; display: none !important;" type="checkbox" value="on" />
              <!--[if mso]>
              </p>
              <![endif]-->
              <table style="table-layout: fixed;" align="center" border="0" cellpadding="0" cellspacing="0" class="container" width="600">
                <tbody>
                  <tr>
                    <td valign="top" align="center" style="padding:18px 0 12px 0;" class="padclear">
                      <table style="table-layout: fixed;" align="center" border="0" width="321" cellpadding="0" cellspacing="0" class="menu container">
                        <tbody>
                          <tr>
                            <td valign="top" align="center">
                              <div id="menu-wrapper">
                                <table width="40" align="left" class="container menu" border="0" cellspacing="0" cellpadding="0">
                                  <tbody>
                                    <tr>
                                      <td valign="top" align="center" style="font-family: Helvetica, Arial, sans-serif; font-size: 13px; line-height: 13px; font-weight: bold;" class="padtb8"><a href="#" class="menu-item" target="_blank" style="color: #ffffff; text-decoration: none; outline: 0px; word-wrap: normal;">SHOP</a></td>
                                    </tr>
                                  </tbody>
                                </table>
                                <!--[if (gte mso 9)|(IE)]>
                                </td>
                                <td valign="top">
                                <![endif]-->
                                <table width="37" align="left" class="mobhide" border="0" cellspacing="0" cellpadding="0">
                                  <tbody>
                                    <tr>
                                      <td valign="top" align="center">&nbsp;</td>
                                    </tr>
                                  </tbody>
                                </table>
                                <!--[if (gte mso 9)|(IE)]>
                                </td>
                                <td valign="top">
                                <![endif]-->
                                <table width="45" align="left" class="container menu" border="0" cellspacing="0" cellpadding="0">
                                  <tbody>
                                    <tr>
                                      <td align="left" style="font-family: Helvetica, Arial, sans-serif; font-size: 13px; line-height: 13px; font-weight: bold;" class="padtb8"> <a href="#" class="menu-item" target="_blank" style="color: #ffffff; text-decoration: none; outline: 0px; word-wrap: normal;">PRESS</a> </td>
                                    </tr>
                                  </tbody>
                                </table>
                                <!--[if (gte mso 9)|(IE)]>
                                </td>
                                <td valign="top">
                                <![endif]-->
                                <table width="37" align="left" class="mobhide" border="0" cellspacing="0" cellpadding="0">
                                  <tbody>
                                    <tr>
                                      <td valign="top" align="center">&nbsp;</td>
                                    </tr>
                                  </tbody>
                                </table>
                                <!--[if (gte mso 9)|(IE)]>
                                </td>
                                <td valign="top">
                                <![endif]-->
                                <table width="90" align="left" class="container menu" border="0" cellspacing="0" cellpadding="0">
                                  <tbody>
                                    <tr>
                                      <td align="left" style="font-family: Helvetica, Arial, sans-serif; font-size: 13px; line-height: 13px; font-weight: bold;" class="padtb8"> <a href="#" class="menu-item" target="_blank" style="color: #ffffff; text-decoration: none; outline: 0px; word-wrap: normal;">LOOKBOOKS</a> </td>
                                    </tr>
                                  </tbody>
                                </table>
                                <!--[if (gte mso 9)|(IE)]>
                                </td>
                                <td valign="top">
                                <![endif]-->
                                <table width="37" align="left" class="mobhide" border="0" cellspacing="0" cellpadding="0">
                                  <tbody>
                                    <tr>
                                      <td valign="top" align="center">&nbsp;</td>
                                    </tr>
                                  </tbody>
                                </table>
                                <!--[if (gte mso 9)|(IE)]>
                                </td>
                                <td valign="top">
                                <![endif]-->
                                <table width="35" align="left" class="container menu" border="0" cellspacing="0" cellpadding="0">
                                  <tbody>
                                    <tr>
                                      <td align="left" style="font-family: Helvetica, Arial, sans-serif; font-size: 13px; line-height: 13px; font-weight: bold;" class="padtb8"> <a href="#" class="menu-item" target="_blank" style="color: #ffffff; text-decoration: none; outline: 0px; word-wrap: normal;">SALE</a> </td>
                                    </tr>
                                  </tbody>
                                </table>
                              </div>
                            </td>
                          </tr>
                        </tbody>
                      </table>
                    </td>
                  </tr>
                </tbody>
              </table>
            </td>
          </tr>
        </tbody>
      </table>
    </td>
  </tr>
</table>
```

Here's the csss to control how the hamburger menu will display within your email.

```css
*[id]#wrapper + table, *[class].container, *[class].menu {min-width:0!important;-moz-text-size-adjust:none;-ms-text-size-adjust:none;-webkit-text-size-adjust:none;width:100%!important;}
*[id]#logo {height:50px;width:182px;}
*[id]#mobile-label {background-color:#ffffff;	cursor:pointer;display:block!important;float:right;padding:4px;padding-right:0;padding-left:0;	-webkit-tap-highlight-color:transparent;width:26px;}
*[id]#mobile-label > b {background-color:#000001;-moz-border-radius:2px;-webkit-border-radius:2px;border-radius:2px;display:block;height:4px;}
*[id]#mobile-label > b + b {margin-top:4px;}
*[id]#menu-wrapper {background-color:#000001;max-height:0;overflow:hidden;-moz-transition:max-height .25s linear;-o-transition:max-height .25s linear;-webkit-transition:max-height .25s linear;transition:max-height .25s linear;}
*[id]#mobile-checkbox:checked + table #menu-wrapper {max-height:350px;}
*[class].menu + .menu {border-top: 1px solid #ffffff;}
*[class].menu-item {color:#ffffff!important;display:block;padding:12px;text-align:center;}
```

**NOTE:** the hamburger menu code must be placed before coding the actual menu
