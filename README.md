# many-to-many
SELECT roles.`name`  from users  inner join roleusers on users.id = roleusers.user_id and roleusers.user_id = 1 inner JOIN roles on roleusers.role_id = roles.id
