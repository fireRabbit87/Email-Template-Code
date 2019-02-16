## Simple Button

This is a super simple button.

```html
<table width="100%" cellspacing="0" cellpadding="0" border="0" bgcolor="#ffffff">
  <tr>
    <td align="center" valign="bottom" style="padding:0 30px 30px 30px;" class="mobpad">
      <table width="100%" cellspacing="0" cellpadding="0" border="0">
        <tr>
          <td align="left">
            <table cellspacing="0" cellpadding="0" border="0">
              <tr>
                <td align="left" style="font-family:arial;font-size:16px;line-height:22px;color:#ffffff;padding:10px 40px;border-radius:7px;-webkit-border-radius:7px;-moz-border-radius:7px;" bgcolor="#222222">
                  <a href="#" target="_blank" style="color:#FFFFFF;">CSS Button</a>
                </td>
              </tr>	
            </table>
          </td>
        </tr>	
      </table>
    </td>
  </tr>
</table>
```

This option is **not** recommended as the rounded corners do not display in some versions of Outlook, as Outlook does not support any of the css for border-radius.
```css
border-radius:XXpx;
-webkit-border-radius:XXpx;
-moz-border-radius:XXpx;
```
You can read more about [border radius](https://www.w3schools.com/cssref/css3_pr_border-radius.asp).

If you want to make the button a fit your mobile at 100%, on line #7, add:
```html
class="container"
```

