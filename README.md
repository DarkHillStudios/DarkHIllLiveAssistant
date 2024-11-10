DarkHill Live Assistant

DarkHill Live Assistant is a cutting-edge, customizable streaming assistant designed to empower content creators on YouTube. Whether you're a solo gamer, a podcast host, or a live event broadcaster, DarkHill Live Assistant makes your streaming experience seamless by automating live chat engagement, enhancing audience interaction, and delivering valuable insights. With planned support for additional streaming platforms like Twitch and Kick, this tool is ready to grow alongside your streaming journey.
Key Features

    Live Chat Management: Easily monitor and respond to messages in real time using a sleek, intuitive interface.
    Custom Commands: Automate your interactions with fully customizable chat commands.
    Notifications: Receive sound notifications for key events such as new subscribers or donations (requires integration with YouTube's API and/or PayPal).
    Stream Health Monitoring: Stay informed with real-time updates on stream performance.
    Active Chatter Tracking: View and manage a list of active viewers to keep track of your audience.
    Authentication Options:
        Authenticate using your YouTube account for seamless access to live chat and channel insights.
        Optional bot account authentication for automated responses and moderation.

Upcoming Features

    Multiplatform Support: Planned expansions for Twitch, Kick, and other platforms.
    Advanced Analytics: In-depth metrics for audience engagement and stream performance.
    Monetization Options: Non-intrusive ads and premium upgrades for additional features.
    Cross-Platform Chat: Unified chat management across multiple streaming services.

Installation

    Clone this repository:

git clone https://github.com/your-username/DarkHillLiveAssistant.git

Navigate to the project directory:

```bash cd DarkHillLiveAssistant```

Install the required dependencies:

```bash pip install -r requirements.txt```

Place your client_secret.json file (YouTube API credentials) in the app/ directory.

Run the application:

```bash python app/main_app.py```

Authentication Instructions

DarkHill Live Assistant uses OAuth 2.0 to securely authenticate your YouTube account.

    Ensure you have set up a project in the Google Cloud Console.
    Download your client_secret.json file and place it in the app/ directory.
    The app will guide you through the authentication process when first run.
    Credentials are securely stored in token.json for subsequent logins.

Optional: Bot YouTube Account

A bot account can be used to:

    Automate responses for frequently asked questions.
    Moderate chat.
    Execute advanced commands without tying them to your personal account.

How to Set Up a Bot Account:

    Create a new YouTube account to act as your bot.
    Authenticate the bot account using the same process as above.
    Select "Bot Account Mode" from the Options menu in the app to activate bot-specific features.

Requirements

    Python: 3.8 or newer.
    APIs:
        YouTube Data API v3.
    Dependencies:
        google-auth
        google-auth-oauthlib
        google-auth-httplib2
        requests
        PyQt6

Install all dependencies with:

```bahspip install -r requirements.txt```

License

This project is licensed under the Apache License 2.0. See the LICENSE file for details.
Contribution Guidelines

We welcome contributions! Here's how you can help:

    Report bugs by opening an issue.
    Suggest new features or enhancements.
    Submit pull requests with improvements or fixes.

Before contributing, please read our CONTRIBUTING.md file.
Support

    FAQ: Refer to the Wiki.
    Discord Community: Join our Discord server to chat with the developers and other users.
    Contact: For direct support, email us at support@darkhillgaming.com.

Disclaimer

DarkHill Live Assistant is provided "as is" without warranty of any kind. By using this software, you agree to comply with YouTube’s Terms of Service and Community Guidelines.

DarkHill Live Assistant: Enhancing live streams, empowering creators, and growing communities—one chat at a time. 🚀

DarkHill Live Assistant is licensed under the [Apache License 2.0](LICENSE).
