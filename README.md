# テーブル設計

## (users) テーブル
## travelersテーブル

| Column                | Type     | Options     |
| ----------------------| -------- | ------------|
| name                  | string   | null: false |
| name_kana             | string   | null: false |
| email                 | string   | null: false |
| encrypted_password    | string   | null: false |

## photographers テーブル

| Column                | Type     | Options     |
| ----------------------| -------- | ------------|
| name                  | string   | null: false |
| name_kana             | string   | null: false |
| email                 | string   | null: false |
| country               | string   | null: false |
| language              | string   | null: false |
| taste                 | string   | null: false |
| encrypted_password    | string   | null: false |



## contacts テーブル

| Column                 | Type       | Options      |
| -----------------------| ---------- | ------------ |
| country                | string     | null: false  |
| fullname               | string     | null: false  |
| mail                   | string     | null: false  |
| tel                    | string     | null: false  |
| budget                 | string     | null: false  |
| shooting_start_at_date | string     | null: false  |
| shooting_time_duration | string     | null: false  |
| comment                | text       | null: false  |

- belongs_to :user