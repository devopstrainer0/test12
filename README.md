# test12

sed -i "s|\${MY_CONFIG_1}|$MY_CONFIG_1|g;s|\${MY_CONFIG_2}|$MY_CONFIG_2|g;s|\${MY_SECRET_KEY}|Y2VydGlmaWNhdGU=|g" deploy.yaml
