# ProtoSpaceのER図

## usersテーブル

| Column     | Type   | Options     |
| ---------- | ----   | ----------- |
| email      | string | null: false |
| password   | string | null: false |
| name       | string | null: false |
| profile    | text   | null: false |
| occupation | text   | null: false |
| position   | text   | null: false |c

## prototypesテーブル

| Column     | Type       | Options     |
| ---------- | ---------- | ----------- |
| titile     | string     | null: false |
| catch_copy | text       | null: false |
| concept    | text       | null: false |
| image      |            |             |
| user       | references |             |

## commentsテーブル

| Column     | Type       | Options     |
| ---------- | ---------- | ----------- |
| text       | text       | null: false |
| prptptype  | references |             |