# VZY OTT Platform Monitoring Dashboard

Real-time monitoring dashboard for VZY OTT platform services.

## 🚀 Live Dashboard

**Dashboard URL:** https://piyushecemangla-stack.github.io/vzy-ott-monitoring/

## 📊 Features

- ✅ Real-time monitoring of 30+ services
- ✅ Auto-refresh every minute
- ✅ Color-coded health status (Green/Orange/Red)
- ✅ CloudWatch integration
- ✅ Service categorization
- ✅ Latency and uptime tracking

## 🎯 Services Monitored

### Frontend & Backend
- VZY Frontend
- SMS Adaptor

### Content Partners
- Zee5, Sony LIV, JS, Fancode
- Hoichoi, Chaupal, Sun Nxt, Hungama

### AWS Services
- S3 Buckets, Step Functions
- Catalogue Adaptor

### Databases
- MongoDB (Content & Users)

### Kaltura CMS
- Central Content Store
- Household & Profile Management
- Device Management
- Concurrency Control
- Playback Service
- KS Token Service

### Dish Backend
- Login Service
- GetUserAPI
- Webhook
- Fliqs Catalogue
- Payment Acknowledgement

### Other Services
- Vyne RE Manager
- SARA Recommendation
- Partner Subscription

## 🔧 Technical Details

- **Region:** ap-south-1 (Asia Pacific - Mumbai)
- **CloudWatch Namespace:** VZY/OTT (auto-detected)
- **Refresh Interval:** 60 seconds
- **Data Source:** AWS CloudWatch

## 📱 Usage

Simply open the dashboard URL in any browser. The dashboard will:
1. Connect to AWS CloudWatch
2. Discover existing monitoring setup
3. Display real-time service health
4. Auto-refresh metrics

## 🛠️ Maintenance

To update service endpoints or configuration, edit `index.html` and push changes.

---

**Built for VZY OTT Platform** | Powered by AWS CloudWatch
