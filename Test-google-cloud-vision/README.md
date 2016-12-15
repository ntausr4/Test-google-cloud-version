# Test-google-cloud-version
測試  Google Cloud Version API

這個範例展示了Vision API辨識照片中有幾張人臉, 有一張圖很有趣包含了一隻猴子, Vision API沒有漏氣不會將猴子當作是人臉

*前置工作&相關知識

Ref Google GitHub
https://github.com/GoogleCloudPlatform/java-docs-samples/tree/master/vision

1.Java 8
2.Twitter application connection
3.Basic knowledge of RxJava is required

*使用 Google Cloud Account 建立一個專案以及 enable Cloud Vision API

設定 googl api console
https://console.developers.google.com/project 

建立完成後，點選專案名稱，進入專案管理頁 (我的第一個使用 google API 專案)
https://console.developers.google.com/iam-admin/projects

安裝 cloud sdk
sudo curl https://sdk.cloud.google.com | bash

安裝路徑
MAC
/Users/Kevin/Dropbox/2Volumes/Develope    (e.g.)

Raspberry Pi
/path/to/

Set the GCLOUD_PROJECT environment variable

Linux:
export GCLOUD_PROJECT=google-cloud-vision    (e.g.)

Windows:
set GCLOUD_PROJECT=google-cloud-vision

Obtain authentication credentials
gcloud beta auth application-default login

Set the GOOGLE_APPLICATION_CREDENTIALS environment variable

Linux:
export GOOGLE_APPLICATION_CREDENTIALS=/Users/Kevin/Dropbox/2Volumes/Develope/API_KEY/google-api-key.json    (e.g.)

Windows:
set GOOGLE_APPLICATION_CREDENTIALS=/path/to/google-api-key.json    (e.g.)

Ref GitHub
https://github.com/shekhargulati/52-technologies-in-2016/tree/master/09-cloudvision