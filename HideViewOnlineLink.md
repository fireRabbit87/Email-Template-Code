## Hide the view online link
This is a good way to hide the view online link, when you're already in the webpage version of the email. This trick utilizes the `_messagecontext` functionality that's available in marketing cloud.
```html
<table align="center" border="0" cellpadding="0" cellspacing="0" class="wrapper" style="width:580px;" width="580">
  <tr>
    <td align="center" class="side" valign="top">
      <table align="center" border="0" cellpadding="0" cellspacing="0" class="wrapper" style="width:540px;" width="540">
        <tr>
          <td align="center" class="white" style="font-family:'Proxima Nova', 'Montserrat', Arial, sans-serif;font-size:15px;color:#ffffff;text-align:center;line-height:18px;padding:10px 0" valign="middle">
            <!--%%[IF _messagecontext !="VAWP" THEN]%%-->
              <a href="%%view_email_url%%" style="font-family:arial, sans-serif;font-size: 12px;color: #ffffff;text-align:left;line-height:17px;text-decoration:underline" target="_blank">view in browser</a>
            <!--%%[ENDIF]%%-->
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>
```
