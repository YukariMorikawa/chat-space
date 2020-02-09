# DB設計

## users table

|Column|Type|Options|
|:----|:----|:---|
|name|string|index:true, null:false, unique:true|
|mail|string|null:false|

# Association
・has_many:groups, through:members
<br>
・has_many:messages
<br>
・has_many:members
<br>
