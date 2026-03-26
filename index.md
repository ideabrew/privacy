# プライバシーポリシー / Privacy Policy

**最終更新日 / Last updated: 2026-03-26**

---

## 日本語

### 1. はじめに

Idea Brew（以下「本アプリ」）は、ユーザーのアイデアを組み合わせてインスピレーションを与えるアプリです。本プライバシーポリシーは、本アプリがどのような情報を扱うかを説明します。

### 2. 収集・保存する情報

**クラウド（Supabase）に保存する情報:**
- 着想（タイトル、本文、タグ）
- 組み合わせカード（タイトル、説明、評価、メモ）
- ユーザーID（ランダム生成されるUUID）
- 認証情報（Apple または Google アカウントでサインインした場合、認証プロバイダーから提供されるメールアドレスおよびユーザー識別子）

これらのデータは、Supabase, Inc.（supabase.com）が提供するクラウドデータベースに、ユーザーIDと紐付けて保存されます。

**認証について:**
本アプリでは、Apple アカウントまたは Google アカウントによるサインインを提供しています。サインイン時に各認証プロバイダーから提供される情報（メールアドレス、ユーザー識別子）を Supabase の認証基盤に保存します。アカウント連携なしで匿名のままご利用いただくことも可能です。

**端末のローカルストレージ（AsyncStorage）にのみ保存する情報:**
- ユーザーID（クラウドと同じIDをローカルにも保持）
- アプリ設定（オンボーディング完了フラグ）
- AI生成結果のキャッシュ（同じ組み合わせの再生成を省くための一時保存）

**AI機能利用時に送信する情報:**
組み合わせカードのAI生成機能を使用する際、入力した着想のタイトルと本文を当社のサーバー（Supabase Edge Functions）経由で OpenAI, LLC に送信します。生成されたカードの内容はクラウドに保存されます。OpenAI へのデータ送信には OpenAI のプライバシーポリシーが適用されます。

### 3. 収集しない情報

本アプリは以下の情報を収集しません：
- 位置情報
- 連絡先
- デバイス識別子（MACアドレス、広告IDなど）
- 利用統計・アナリティクス

### 4. 第三者サービスへの情報提供

本アプリは以下のサービスプロバイダーを利用します。各社のプライバシーポリシーが適用されます：

- **Supabase, Inc.**（データ保存・認証基盤）: https://supabase.com/privacy
- **OpenAI, LLC**（AI生成処理）: https://openai.com/privacy
- **Apple Inc.**（Sign in with Apple による認証）: https://www.apple.com/legal/privacy/
- **Google LLC**（Google サインインによる認証）: https://policies.google.com/privacy

これらのサービスプロバイダーは、本アプリのサービス提供目的以外にデータを使用しません。上記以外の第三者にデータを販売・提供・開示することはありません。

### 5. データの保存と削除

着想・組み合わせカードはクラウド（Supabase）に保存されます。**アプリをアンインストールしてもクラウド上のデータは削除されません。** データを完全に削除するには、アンインストール前にアプリ内の削除機能をご利用ください（アプリ内から削除するとクラウドからも削除されます）。

ローカルのみに保存されているデータ（アプリ設定、AIキャッシュ）はアンインストールにより削除されます。

### 6. お子様のプライバシー

本アプリは13歳未満のお子様を対象としていません。

### 7. プライバシーポリシーの変更

本ポリシーを変更する場合は、アプリのアップデートとともにお知らせします。

### 8. お問い合わせ

プライバシーに関するご質問は、App Store / Google Play のサポートページよりお問い合わせください。

---

## English

### 1. Introduction

Idea Brew ("the App") helps users combine ideas to spark inspiration. This Privacy Policy explains what information the App handles.

### 2. Information We Collect and Store

**Information stored in the cloud (Supabase):**
- Inspirations (title, body text, tags)
- Combination cards (title, description, ratings, notes)
- User ID (a randomly generated UUID)
- Authentication information (if you sign in with Apple or Google, the email address and user identifier provided by the authentication provider)

This data is stored in a cloud database provided by Supabase, Inc. (supabase.com), associated with your user ID.

**Authentication:**
The App offers sign-in via Apple or Google accounts. When you sign in, information provided by the authentication provider (email address, user identifier) is stored in the Supabase authentication system. You may also use the App anonymously without linking an account.

**Information stored only on your device (AsyncStorage):**
- User ID (the same ID as above, cached locally)
- App settings (onboarding completion flag)
- AI generation cache (temporary storage to avoid regenerating the same combinations)

**Information sent when using AI features:**
When using the AI card generation feature, the title and body text of your inspirations are sent to OpenAI, LLC via our server (Supabase Edge Functions) for processing. The generated card content is saved to the cloud. OpenAI's privacy policy applies to data sent to OpenAI.

### 3. Information We Do NOT Collect

The App does not collect:
- Location data
- Contacts
- Device identifiers (MAC address, advertising ID, etc.)
- Usage statistics or analytics

### 4. Third-Party Service Providers

The App uses the following service providers. Their respective privacy policies apply:

- **Supabase, Inc.** (data storage and authentication): https://supabase.com/privacy
- **OpenAI, LLC** (AI generation): https://openai.com/privacy
- **Apple Inc.** (Sign in with Apple authentication): https://www.apple.com/legal/privacy/
- **Google LLC** (Google Sign-In authentication): https://policies.google.com/privacy

These providers do not use your data beyond what is necessary to provide services to this App. We do not sell, share, or disclose your data to any other third parties.

### 5. Data Storage and Deletion

Inspirations and combination cards are stored in the cloud (Supabase). **Uninstalling the App does not delete your cloud data.** To fully delete your data, please use the in-app deletion features before uninstalling (deleting items within the App also removes them from the cloud).

Data stored only on your device (app settings, AI cache) is deleted when you uninstall the App.

### 6. Children's Privacy

The App is not directed to children under the age of 13.

### 7. Changes to This Policy

We will notify you of any changes to this policy via app updates.

### 8. Contact

For privacy-related questions, please contact us through the support page on the App Store or Google Play.
