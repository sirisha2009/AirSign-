# AirSign-
AirSign: a browser-based tool that turns sign language handshapes into text and speech in real time, using hand tracking and on-device machine learning.


AirSign helps bridge the communication gap between sign language users and people who don’t know sign language. It uses a webcam to track your hand, recognizes the sign you’re making, and turns it into text and spoken words, live.

Features

Recognizes fingerspelling letters and common word signs
Teach it any new sign in about 30 seconds (works for ASL, Indian Sign Language, or custom gestures)
Runs fully in the browser, so no installation, no server, and no video leaves your device

How it works: MediaPipe Hands detects 21 landmarks on the hand, the app converts them into a size-independent fingerprint, and a k-nearest-neighbours classifier matches it against the signs you recorded.

Built with: HTML, JavaScript, MediaPipe Hands (Google), Web Speech API
