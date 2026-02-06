# 🚨 SustAInex  
**AI-Powered Smart City Disaster Response Platform**

An intelligent incident detection and emergency response system powered entirely by **Google Gemini 3** for real-time AI vision analysis, situational awareness, and automatic authority alerts.

---

## ✨ Key Features

- 🔍 **Incident Detection** - AI vision analysis of images/videos (fire, flood, accidents, building collapse, crowds)
- 📍 **Location Detection** - GPS/IP-based location with emergency resource mapping
- 💬 **Situational Awareness** - AI-powered guidance with precautions and action steps
- 🗣️ **Multilingual Support** - Real-time translation to regional languages (Tamil, Hindi, Kannada, Telugu, Bengali, Chinese, Japanese, etc.)
- 🚨 **Authority Alerts** - Automated SMS alerts to emergency services
- 🗺️ **Live Map** - Real-time incident tracking with severity visualization
- 👥 **Community Feed** - Real incident reports from users in your area

---

## 🏗️ Technology Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | Next.js 15, React 18, TypeScript, Tailwind CSS, Shadcn/ui |
| **Maps & Visualization** | Leaflet, Recharts |
| **AI/ML** | **Google Gemini 3 Flash** (100% AI powered) |
| **Backend** | Next.js API Routes |
| **Alerts** | Twilio (optional) |
| **Media Storage** | Cloudinary (optional) |

---

## 📊 Gemini 3 Feature vs Our Technique

| Feature | Gemini 3 Capability | Our Implementation |
|---------|-------------------|-------------------|
| **Vision Analysis** | Multi-modal image/video understanding with scene detection | Real-time incident classification (Fire, Flood, Accident, Building Collapse, Crowds, Environmental Hazards) |
| **Language Understanding** | Advanced NLP with contextual comprehension | Parsing incident reports and generating situational awareness guidance |
| **Text Generation** | High-quality, coherent text output | Creating precautions, action steps, and emergency instructions |
| **Multilingual Support** | 100+ language translation capability | Supporting  regional languages with automatic detection |
| **Text-to-Speech** | Natural voice synthesis | Emergency audio alerts in user's regional language |
| **Speed & Latency** | Sub-second response times | Real-time incident analysis (<2 seconds) |
| **Accuracy** | Best Accuracy in scene understanding | High-precision incident type classification |
| **Context Awareness** | Multi-turn conversation with memory | Awareness of location, severity, and regional emergency protocols |
| **Cost Efficiency** | Free tier with generous limits | Optimized API calls for scale without high costs |

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm 9+ or yarn
- Gemini API Key (free at [ai.google.dev](https://ai.google.dev))

### Installation

```bash
# Clone repository
git clone <repository-url>
cd smartcity-sentinel

# Install dependencies
npm install

# Setup environment variables
echo "GEMINI_API_KEY=your_api_key_here" > .env
echo "GOOGLE_GENAI_API_KEY=your_api_key_here" >> .env

# Start development server
npm run dev

# Open http://localhost:9002
```

### Usage

1. **Upload Media** - Select an image or video of the incident
2. **Select Language** - Choose English or regional language
3. **View Analysis** - Get incident type, severity, and precautions
4. **Check Map** - See incident location and nearby emergency services
5. **Authorities Notified** - SMS alerts sent automatically

---

## 📁 Project Structure

```
src/
├── app/                          # Next.js app directory
├── ai/                           # Gemini 3 AI flows
│   └── flows/                   # Genkit flows for AI operations
│       ├── analyze-uploaded-media-for-incident.ts
│       ├── provide-situational-awareness.ts
│       ├── offer-multilingual-support.ts
│       └── send-emergency-alert.ts
├── components/                   # React components
├── lib/                         # Utilities
└── types/                       # TypeScript definitions
```

---

## 🔑 Environment Variables

```env
# Required - Gemini API Key
GEMINI_API_KEY=your_gemini_api_key_here
GOOGLE_GENAI_API_KEY=your_google_genai_api_key_here

# Optional - SMS Alerts
NEXT_PUBLIC_TWILIO_ACCOUNT_SID=your_twilio_sid
NEXT_PUBLIC_TWILIO_AUTH_TOKEN=your_twilio_token
NEXT_PUBLIC_TWILIO_FROM=+1234567890

# Optional - Media Storage
NEXT_PUBLIC_CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

---

## 🔄 Incident Response Flow

```
Upload Media 
    ↓
Gemini 3 Vision Analysis (Incident Detection)
    ↓
Select Language
    ↓
Gemini 3 Language Processing (Situational Awareness)
    ↓
Gemini 3 Translation (Multilingual Support)
    ↓
Alert Authorities (SMS)
    ↓
Display Results & Map View
```

---

## 🌐 Supported Languages

All global languages via Gemini 3 translation, with priority support for:
- Hindi, Tamil, Kannada, Telugu, Bengali
- Mandarin, Japanese, Korean
- And 90+ more languages

---

## 📱 Device Support

✅ Desktop (Windows, Mac, Linux)  
✅ Mobile (iOS, Android)  
✅ Tablets  
✅ Fully Responsive Design  

---

## 🛠️ Available Commands

```bash
npm run dev      # Development server
npm run build    # Production build
npm start        # Start production server
npm run lint     # Lint code
npx tsc --noEmit # Type check
```

---

## ✅ Quick Start Checklist

- [ ] Node.js 18+ installed
- [ ] Repository cloned
- [ ] Dependencies installed (`npm install`)
- [ ] `.env` file created with Gemini API key
- [ ] Dev server started (`npm run dev`)
- [ ] Browser opened to `http://localhost:9002`
- [ ] Image uploaded and analyzed
- [ ] Language selected
- [ ] Results displayed on map

---

## 📄 License & Credits

**SustAInex** - Nextus Sustainable Smart City Initiative  
Built with Google Gemini 3   
Made with ❤️ for emergency response and public safety

---

