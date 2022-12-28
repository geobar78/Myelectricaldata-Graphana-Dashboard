# Myelectricaldata-Graphana-Dashboard
Based on m4dm4rtig4n dashboard, I just updated the panel with the new db DATABASE.RETENTION

Basé sur le dashbord myenedis de m4dm4rtig4n, j'ai juste mis à jour les panels avec la configuration de la nouvelle base utilisée par la v0.8.x de l'addon Myelectricaldata

Only work with Influxdb 1.8.x / Ne fonctionne qu'avec InfluxDB <= 1.8.x

Note that to use the dashboard you will need in Graphana / Notez que pour utiliser le dashboard vous aurez besoin dans Graphana de :

Add the plugins / Ajouter les plugins:

grafana-piechart-panel

farski-blendstat-panel

blackmirror1-singlestat-math-panel


Add the data source / Ajouter la datasource DATABASE (create in Influxdb DATABASE Bucket RETENTION)

![image](https://user-images.githubusercontent.com/75928935/208238073-b9543fff-e2fc-47d2-b559-6665d0708795.png)

![image](https://user-images.githubusercontent.com/75928935/209825354-11c9b0c2-1f99-46fd-9ab9-96177852446a.png)

Dans Graphana :

![Config datasources](https://user-images.githubusercontent.com/75928935/208145020-567beac6-5b6b-4870-bb44-afb3b662c169.jpg)

![image](https://user-images.githubusercontent.com/75928935/209827016-e74f69aa-9a67-439e-9e96-ca009e736802.png)


![image](https://user-images.githubusercontent.com/75928935/209826576-e64f752b-9a2b-4076-b91a-66b1c16267b1.png)



Do not forget to configure your variables in the dashboard settings (pdl, prices...) / N'oubliez pas de mettre à jour vos variables dans la configuration du dashboard





![variables](https://user-images.githubusercontent.com/75928935/208123117-a82f6f2e-2997-4a96-aaa2-649cf5c65aa9.jpg)

It should give you something like this / ça devrait vous donner quelque chose comme ça :

![208099481-cd3b3153-9ae9-4f0f-825f-d138f5e411e9](https://user-images.githubusercontent.com/75928935/208125236-c716905e-4880-4aae-9f0b-ce0c3dc14b32.png)

![208099536-b3df92d9-9115-40d3-976e-7c1d44cffd65](https://user-images.githubusercontent.com/75928935/208125279-9dcb609c-f00a-4b8e-a28e-ed0dceec0783.png)

![208099593-c228fcd7-b1e4-48ed-a7a3-ba7abebb50ee](https://user-images.githubusercontent.com/75928935/208125317-0655d357-5ed8-446d-b19c-76c6498c896c.png)

