# Real World Example

Your console notification program works really, really well.
These are the new requirements for the application.

* Network operations team would love to use an API to send files from scripts without using the console application.
* Besides raw text, the library needs to handle reading the body of the email from an XML file. Tthis is a sample of the structure of the XML: 

```xml
<email>
  <body>this is what needs to be read</boby>
</email>
```

## The Exercise

These new requirements need to be implemented, but also take the chance to apply the SRP principle to whatever solution you come up with.

Do not get ahead of yourself. Just use this SOLID principle. Remember, this is only the first exercise; more to come.<br/>
You will be using the resulting code as a baseline for further exercises.


### Hint #1

Let's assume only two responsibilities: sending the email and reading the body.

### Hint #2

`MailSender` and `FormatReader` are suitable names for each responsibility.
