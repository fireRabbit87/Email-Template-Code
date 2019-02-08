## View online link

This is your basis view online link, Salesforce Marketing Cloud requires this at the time of send, and won't send an email without this in place specifically;

```html
%%view_email_url%%
```

This is what it looks like if you used it in conjunction with the template
```html
<table width="100%" cellspacing="0" cellpadding="0" border="0" bgcolor="#ffffff">
  <tr>
    <td align="center">
      <table width="100%" cellspacing="0" cellpadding="0" border="0" bgcolor="#222222">
        <tr>
          <td align="right" style="font-family:arial;font-size:14px;color:#ffffff;padding:20px 30px 10px 30px;" class="textcenter">
            <a href="%%view_email_url%%" target="_blank" style="text-decoration:underline;color:#ffffff;">view online</a>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>
 ```
 
 May require changes made to the alignment, color, background color, font size and padding.
