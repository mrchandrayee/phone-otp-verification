# Phone OTP Verification

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/phone-otp-verification/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable, responsive frontend reconstruction of the supplied 20.5-second screen recording.

## Screen flow visible in the video
1. **Phone OTP verification** — heading at the top.
2. **Verify Your Phone** — helper text: “We will send you a 4-digit one-time password.”
3. Mobile number input with placeholder `Enter Mobile Number`.
4. `Send OTP` button.
5. **Enter OTP** — helper text: “We've sent a code to your phone. (Use demo code: 1234)”
6. Four OTP digit boxes and `Verify Code` button.
7. Incorrect code feedback: `Incorrect OTP! Please try again. Hint: 1234`
8. Success screen: `Verification Successful!` / `Your account has been safely verified.`

## Demo behaviour
- Enter a mobile number containing 7–15 digits and select **Send OTP**.
- Enter `1234` to see the success screen.
- Any other four-digit code shows the incorrect OTP message.
- OTP boxes auto-advance, support backspace/arrow navigation, and accept pasted digits.
- “Change phone number” returns to the phone input screen; “Verify another number” resets the flow.

## Run
Open `index.html` in a modern browser, or:
```bash
python3 -m http.server 8000
```
Then visit http://localhost:8000.

## Source fidelity and limits
The video shows a phone-number entry screen, a four-digit OTP screen, an incorrect-code message, and a success screen. The visible copy and flow are reproduced. The source recording does not show a complete original HTML/CSS/JavaScript repository; the page styling and interaction code here are a functional reconstruction based on the rendered screens. No SMS is sent and no real phone ownership is verified: `1234` is a local demo code only. A production implementation needs a server-side OTP provider and verification endpoint.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
