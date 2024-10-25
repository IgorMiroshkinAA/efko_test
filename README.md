## Yii2 Basic Setup:
```bash
git clone https://github.com/yiisoft/yii2-app-basic.git .
docker-compose up -d
```

## Если проект будет развернут, необходимо обновить config/db.php
```bash
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=db;dbname=yii2basic',
    'username' => 'yii2',
    'password' => 'yii2_password',
    'charset' => 'utf8',
];
```
