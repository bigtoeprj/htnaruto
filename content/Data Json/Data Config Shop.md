---
tags: []
---
Vị trí file config: **\Assets\Resources\Config\ShopConfig.txt**

```
"ChoDen": {
		"resetPrice": -1,
		"resetTime": {
			"timeResetType": "Daily",
			"value": 0
		},
```

**Tên Shop**
ChoDen, VongQuay, HuyetTe, HamDoi, DauTruong, MeCung, DaiHaiTac

- "resetPrice": -1 là không có reset. False.
- timeResetType: Daily, Weekly, Monthly, Monthly_User
- value: CN là 0, Thứ 2 là 1,... thứ 7 là 6.

```
"shopItems": [
			{
				"id": 1,
				"currency": "ITEM_Kim_Cuong",
				"price": 150,
				"limit": 1,
				"phanThuongRates": [
					{
						"id": 1,
						"phanThuong": {
							"codeName": "ITEM_Coc_bia_vang",
							"quantity": 1
						},
						"rate": 1
					}
				]
			},
```

- id: vị trí item k được trùng nhau
- currency: code name của Item trong file 04, dùng gì để mua trong shop
- phanThuongRates: cái này là cho các phần thưởng khi làm mới có rate random ra trong danh sách đó.
