

# ❌ Type-based (current)              # ✅ Feature-based (proposed)
src/
├── components/                        src/
│   ├── billing/                       ├── features/
│   ├── realtime/                      │   ├── billing/
│   └── upload/                        │   │   ├── components/
├── stores/                            │   │   ├── composables/
│   ├── billing.store.js               │   │   ├── store/
│   ├── chat.store.js                  │   │   └── services/
├── composables/                       │   ├── chat/
│   ├── useBilling.js                  │   ├── upload/
│   └── useChat.js                     │   └── notifications/
