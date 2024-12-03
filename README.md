<h1>Send an email using C#</h1>

Just download emailSender folder, and change data, such
 ```
string fromMail = "FromEmail@xxxx.com"; 
string fromPassword = "yourAppPassword";
```
and

```
message.To.Add(new MailAddress("ToEmail@xxxx.com"));
message.Body = "<html><body> TEXT HERE </body></html>";
```

also  here ```string fromPassword = "yourAppPassword";``` you should paste your 16 digit app password. You can read how to do that <a href="https://support.google.com/accounts/answer/185833?hl=en">here</a>
