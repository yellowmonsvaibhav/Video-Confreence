# Video Confreence Folder Structure (Step 1)

```text
.
├── app/
│   ├── _layout.tsx
│   ├── index.tsx
│   ├── (auth)/
│   │   ├── _layout.tsx
│   │   └── login.tsx
│   ├── (tabs)/
│   │   ├── _layout.tsx
│   │   ├── dashboard.tsx
│   │   ├── chat.tsx
│   │   └── settings.tsx
│   ├── chat/
│   │   └── [channelId]/
│   │       └── index.tsx
│   ├── meeting/
│   │   └── [roomId]/
│   │       └── index.tsx
│   └── pricing/
│       └── index.tsx
├── assets/
│   ├── fonts/
│   ├── icons/
│   └── images/
├── components/
│   ├── chat/
│   ├── common/
│   ├── dashboard/
│   ├── meeting/
│   └── paywall/
├── config/
├── hooks/
├── lib/
│   ├── api/
│   ├── calendar/
│   ├── chat/
│   ├── payments/
│   └── video/
├── services/
│   ├── firebase/
│   ├── google/
│   ├── revenuecat/
│   └── stream/
├── store/
├── types/
├── utils/
├── app.json
└── package.json
```
