# Welcome to Service Marketplace!

Service Marketplace is a platform that seamlessly integrates with Agentverse, Google Calendar, WhatsApp, and DeltaV to provide users with a comprehensive solution for managing their events, bookings, and services. Users can onboard using their Google account, grant access to their Agentverse and Google Calendar accounts, and verify their WhatsApp number. Once onboarded, users can create events in their Google Calendar, which are then read by their agent. The agent notifies users on WhatsApp about relevant events and assists in finding and booking services. The platform utilizes the Dorado network and FET for seamless payment integration, deducting 0.001 FET from the user's wallet for each session. With a user-friendly interface and intelligent AI engine, Service Marketplace offers a convenient and efficient solution for users to manage their schedules and bookings effortlessly.

![Service MarketPlace Daiagram](https://github.com/fetchai/fetchai-labs/blob/5fa280045278c9883dddbc559397836accca24dc/ServiceMarketPlace/media/smp-dfd.jpg)

## Guide:

### Prerequisites

Before getting started, ensure you've completed the following:

- 📝 Onboarded on Service Marketplace using your Google account.
- 🔗 Granted access to your Agentverse account and Google Calendar.
- 🔐 Verified your WhatsApp number.
- 👤 Completed your user profile as a consumer or both consumer and provider.

### How it works:

1. Agent-initiated conversation after reading your calendar events:

📅 **Create Event in Google Calendar**: Begin by creating events in your Google Calendar. Remember to include `agent@fetch.ai` as an attendee, detailing date, time, and event description.

⏰ **Agent Event Fetching**: Your agent reads events from Google Calendar every 3 minutes, focusing on those where `agent@fetch.ai` is an attendee.

📲 **WhatsApp Notification**: Upon finding a relevant event, the agent notifies you on WhatsApp, providing event details and prompting for action.

🤖 **AI Engine Processing**: Upon confirmation, the event description is analyzed by the AI engine to determine required tasks.

🔍 **Service Search**: The agent searches for relevant services within Agentverse based on identified tasks.

💬 **WhatsApp Service Selection**: Receive a list of suggested services on WhatsApp. Select your desired service for further actions.

🔄 **Reset Conversation**: Reset the conversation at any time by messaging "reset" on WhatsApp, effectively clearing the session.


2. User-initiated conversation via WhatsApp or DeltaV:

- 🚀 Send messages from DeltaV or WhatsApp to the agent, such as "find me x service".
- 🔍 The agent suggests available services matching your request.
- 📅 Provide necessary details like date, time, and location.
- 👤 Choose a service provider from the available options.
- 🤝 The agent negotiates and confirms the booking.
- 🔔 Both consumer and provider are notified, and a booking event is created in their calendars.
- 🔄 Reset the conversation if needed.


### Payment Flow and Wallet Integration:

💳 **Payment Flow using Dorado Network and FET**:

Seamlessly manage payments using the Dorado network and FET. Each conversation session, from start to reset, incurs a charge of 0.001 FET, deducted from your wallet.

🔒 **Wallet Integration**:

Your user agent handles payments, deducting amounts from your wallet to ensure seamless service. If your wallet balance is insufficient, appropriate messages are provided to guide you through the top-up process.

### Understanding Sessions:

A session refers to the timeframe between the start and reset of a conversation with your agent.


## Integration:

🔗 **Agentverse**: Seamlessly integrate with our Agentverse network for deploying your service agent.

🧠 **AI engine**: Utilize AI engine for intelligent suggestions and recommendations by breaking down event descriptions into smaller tasks.

🚀 **DeltaV**: Communicate with agents through DeltaV, similar to WhatsApp.

📅 **Google Calendar**: Sync your events and bookings effortlessly, with agents having read and write access.

📱 **WhatsApp**: Communicate with agents for quick updates, bookings, and assistance.


## Screens:

👤 **User Profile**: Personalize your experience and manage your preferences effortlessly.

📅 **Booking Dashboard**: Stay organized with a centralized dashboard for all your bookings, including ratings received/given.

👩‍💼 **Agent Profile**: Gain insights into your running agents, including agent address, wallet details, and transaction history.


## Troubleshooting

If you encounter any issues while accessing or need further assistance, please feel free to raise issues [here](https://github.com/fetchai/fetchai-labs/issues/new?assignees=coderlktripathi&amp;labels=ServiceMarketPlace&amp;projects=&amp;template=bug-report.md&amp;title=%5BBUG%5D).
