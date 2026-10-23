# 🏥 PulseCare — Quarantine Ward Operations Dashboard

A responsive healthcare operations dashboard prototype for visualizing quarantine ward activities, patient monitoring, temperature readings, and clinical workflows.

🔗 **Live Demo:** https://pulsecare-anand-2026.vercel.app/

## ✨ Features

- 📊 **Ward Overview** — Bed occupancy, daily readings, doctor visits, and ward status.
- 🩺 **Patient Monitoring** — Patient details, temperature status, search, and filtering.
- 🌡️ **Temperature Management** — Interface for recording and reviewing temperature readings.
- 👨‍⚕️ **Doctor Rounds** — Scheduled rounds and visit progress indicators.
- 📈 **Analytics Dashboard** — Sample operational metrics and performance summaries.
- 👥 **Care Team** — Staff information, roles, and shift coverage.
- ⚙️ **Workspace Settings** — Demonstration controls for ward configuration and notifications.
- 📱 **Responsive UI** — Layout designed for desktop and mobile screens.

*Features and actions should be considered prototype functionality unless verified in the current implementation.*

## 🛠️ Technology Stack

- **HTML5** — Page structure
- **CSS3** — Styling, responsive layouts, Grid, and Flexbox
- **JavaScript** — UI interactions, navigation, search, and filtering
- **Google Fonts** — Typography, if enabled in the application
- **Git & GitHub** — Version control and source code hosting
- **Vercel** — Deployment and web hosting

## 📁 Project Structure

```text
pulsecare-quarantine-ops/
├── index.html       # Main HTML page
├── styles.css       # Styling and responsive layout
├── app.js           # Application logic and interactions
├── README.md        # Project documentation
└── .gitignore       # Files excluded from Git
```

*This structure assumes these are the actual filenames in your project. Update it if your repository differs.*

## 🚀 Run Locally

**Option 1: Browser**

Open `index.html` in a modern web browser.

**Option 2: VS Code Live Server**

1. Open the project folder in VS Code.
2. Install the Live Server extension if needed.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

**Option 3: Python**

```bash
python -m http.server 8000
```

Open http://localhost:8000 in your browser.

## 🌐 Deployment

The application is deployed on Vercel.

**Live Application:** https://pulsecare-anand-2026.vercel.app/

To deploy your own copy, import the GitHub repository into [Vercel](https://vercel.com/), select the project root, and configure it according to the actual static site setup.

## 🔒 Limitations & Security

- This is a frontend demonstration using sample data.
- No production backend, database, or authentication is claimed.
- Interface interactions do not necessarily represent persistent or server-side operations.
- Do not enter real patient information or publish credentials, API keys, or environment secrets.
- Production use would require secure authentication, access controls, persistent storage, audit logging, and appropriate privacy and clinical review.

## 🔮 Future Enhancements

- Backend and database integration
- Secure authentication and role-based access
- Automated temperature alerts and monitoring
- Patient discharge and outcome tracking
- Persistent clinical records and audit logs
- Automated testing and accessibility improvements


---

*PulseCare is a demonstration and portfolio project, not a validated clinical system or a substitute for professional medical judgment.*
