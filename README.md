# Tipjarexpress
Open-source SDK for seamless in-app tipping. Integrate in 3 lines of code, enable &lt;5-second payments, and let creators keep 85%+ of tips

[![License](License)(https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Android CI](https://github.com/your-org/tip-jar-express/actions/workflows/android-ci.yml/badge.svg)](https://github.com/your-org/tip-jar-express/actions)

Designed for clarity, scalbility,and community contribuition. Content creators lose 40% of potential tips due to complex payment flows, platform fees, and fragmented donation systems.


## Why Tip Jar Express?
### The Problem
-  Fragmented payment links disrupt user experience
-  30% platform fees drain creator earnings
-  Mobile tipping requires 5+ steps

### Our Solution
-  **3-line SDK integration** for developers
-  **<5 second** one-tap tipping flow
-  Creators keep **85%+** of every tip
-  Beautiful, customizable UI components

## How It Works
```kotlin
// 1. Initialize SDK
TipJar.init REVENUECAT_goog_PWQrXqKlapcMabkjPlTzWexTXjq)

// 2. Add Tip Button
TipJar.showTipButton(activity, containerView)

// 3. Handle callbacks (optional)
TipJar.setOnTipListener { success, amount -> 
    showConfetti() 
}
