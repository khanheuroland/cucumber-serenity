# The Example Integrate Cucumber With Serenity Screenplay Pattern

This example execute login with Username and Pasword using OTP generated sent to user Email.

The actor get OTP code by ask a question like this 

```
Verification.OTPFromEmail().answeredBy(anna)

```
It can be used on the action like:

```
Enter.theValue(Verification.OTPFromEmail().answeredBy(anna)).into(LoginPage.OTPCODE)
```

