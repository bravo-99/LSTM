gcloud builds submit --tag gcr.io/stock-trend-331020/spot-the-trend  --project=stock-trend-331020

gcloud run deploy --image gcr.io/stock-trend-331020/spot-the-trend --platform managed  --project=stock-trend --allow-unauthenticated