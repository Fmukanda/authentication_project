# authentication_project
```
frontend/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   ├── auth/
│   │   ├── login/
│   │   │   └── page.tsx
│   │   ├── register/
│   │   │   └── page.tsx
│   │   └── layout.tsx
│   ├── dashboard/
│   │   ├── page.tsx
│   │   ├── profile/
│   │   │   └── page.tsx
│   │   └── layout.tsx
│   └── api/
│       └── auth/
│           └── route.ts
├── components/
│   ├── auth/
│   │   ├── LoginForm.tsx
│   │   ├── RegisterForm.tsx
│   │   └── ProtectedRoute.tsx
│   ├── ui/
│   │   ├── Button.tsx
│   │   ├── Input.tsx
│   │   ├── Card.tsx
│   │   └── Modal.tsx
│   └── layout/
│       ├── Header.tsx
│       └── Sidebar.tsx
├── lib/
│   ├── api.ts
│   ├── auth.ts
│   └── utils.ts
├── store/
│   ├── authStore.ts
│   └── userStore.ts
├── styles/
│   └── globals.css
├── public/
│   └── images/
├── .env.local
├── package.json
└── tailwind.config.ts
```
```
backend/
├── core/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── api/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   ├── permissions.py
│   ├── authentication.py
│   └── urls.py
├── manage.py
└── requirements.txt
```

```
Test Credentials:
------------------------------
Admin: admin@uberauth.com / AdminPassword123!
Rider: alice@example.com / TestPassword123!
Driver: bob@example.com / TestPassword123!
Unverified: diana@example.com / TestPassword123!
------------------------------
```
