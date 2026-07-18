# Restaurant Seat Alert

飲食店の空席・限定メニュー・クーポン通知

## Repository

Recommended repository name: `restaurant-seat-alert`

## Domain candidates

First candidate: `seatalert.jp`

Other candidates:

- `seatalert.jp`
- `akimise.jp`
- `meshiwatch.jp`
- `couponalert.jp`

## Concept

空席、限定メニュー、値引き、クーポンを通知し、予約送客と店舗掲載へつなげる飲食通知サービス。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 予約送客
- クーポン課金
- 店舗掲載
- 広告枠
- PR記事

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
