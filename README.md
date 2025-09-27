
# MoSPI Survey & Analytics Platform

MoSPI is a modern survey management and analytics app inspired by the Ministry of Statistics & Programme Implementation (Government of India). It enables users to create, manage, and analyze official surveys with advanced features, including AI-powered assistance.

## Key Features

- **Survey Creation & Customization:** Build and edit surveys with flexible question types and modules.
- **Survey Profiles & Metadata:** Browse official survey profiles and details, including domains, periodicity, and key indicators.
- **Response Collection & Analysis:** Collect responses, view analytics, and visualize data with charts and quality indicators.
- **AI Chatbot Helper:** Floating Gemini-powered chatbot for guidance on survey design, analytics, and best practices.
- **Question Bank Management:** Access and manage official question banks and survey details.
- **User Authentication & Consent:** Secure sign-in and privacy-focused consent forms.
- **Multi-language Support:** Switch survey language for broader accessibility.
- **Survey Export & Reporting:** Export survey data and access latest official reports.
- **Recent Activity & Quick Actions:** Track recent survey activity and perform common tasks quickly.

## Technologies Used

- **React Native** (Expo)
- **expo-router** for navigation
- **Google Gemini API** for AI chatbot
- **TypeScript** for type safety
- **NativeWind** for styling
- **Lucide Icons** for UI

## Setup

1. Copy `.env.example` to `.env` and add your Gemini API key:
	```
	EXPO_PUBLIC_GEMINI_API_KEY=your_key_here
	```
2. Install dependencies:
	```
	npm install
	```
3. Start the development server:
	```
	npm run dev
	```

## Usage

- Tap the purple "Ask" bubble to open the AI chatbot.
- Navigate tabs for Home, Create, Survey, Analytics, and Settings.
- View official survey profiles and download reports.
- Export survey data and view analytics.

## Privacy

- User responses are confidential and used only for official statistical purposes.
- AI chatbot queries are sent to Google APIs; avoid sharing personal or sensitive information.
- Data retention follows government policy (5 years).

## Customization

- Edit `components/Chatbot.tsx` for chatbot prompt, model parameters, and UI.
- Adjust survey modules and question types in `SurveyBuilder.tsx`.

## Contribution

Contributions are welcome! Please open issues or pull requests for bug fixes, improvements, or new features.


