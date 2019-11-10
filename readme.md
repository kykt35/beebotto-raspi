ref https://qiita.com/westvirginia/items/47437d547485cd2784ef

.env
beebotto.comから取得
TOPIC="cannel"/"resouce"
TOKEN=token_XXXXXXXXXXX

beebotteのコンソールから、subscribe起動

ビルド
docker-compose build

コンテナに入る
docker-compose run --rm python3 /bin/bash

cd work

wget https://beebotte.com/certs/mqtt.beebotte.com.pem -P ~/work

python3 smarthome.py


beebotteのコンソールから、publishからテスト送信
