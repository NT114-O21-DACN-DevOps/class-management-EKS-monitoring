﻿# Kubernetes-monitoring
## Sau khi chạy workflow xong thì sử dụng kubectl get cm prometheus-alertmanager  -n prometheus -o yaml > cm_alert.yaml, sau đó sửa file này để cấu hình gởi qua email theo format của file ở trên. Rồi apply, sau đó xóa pod alertmanager cũ.
