# 💉 Hayat Pharmacy Vaccine Recommendation Tool

A comprehensive, user-friendly web application that provides personalized vaccine recommendations based on CDC guidelines. Designed specifically for pharmacy use to help patients understand which vaccines they need based on their age, health profile, and vaccination history. Updated for 2025-2026. 

*As of Sep 1st, 2026 the COVID vaccine recommendation is still unclear, Hayat has obtained a CPA to provide wide coverage of COVID vaccines*

**One page purely on HTML and CSS codes**, you can drop this page into your pharmacy's website easily, by copying and pasting the full page code or add this html page to your website and point a link to it. Search "hayat pharmacy" in the code and replace to match your pharmacy's name for easy integration.

## 🌟 Features

### **Organized Vaccine Categories**
- **Primary 2026 Vaccines**: Flu 2025 and COVID-19 2025
- **Pneumonia Vaccines**: CDC Option B compliant (PCV15/PCV20) with detailed history tracking
- **Age-Related Vaccines**: RSV (≥60 years) and Shingrix (≥50 years)
- **Routine Vaccines**: Tdap, Hepatitis A/B, MMR, Varicella, Meningococcal, HPV
- **Travel Vaccines**: Typhoid (Vivotif), Yellow Fever (YF-Vax), Japanese Encephalitis, etc.

### **Smart Recommendations**
- Age-based vaccine suggestions following CDC guidelines
- Differentiated flu vaccine recommendations (standard vs. high-dose for ≥65 years)
- Comprehensive pneumonia vaccine history tracking with Option B preference
- Real-time recommendations based on patient input

### **Special Features**
- **Yellow Fever Alert**: Automatic notification with special handling instructions
- **Pneumonia History Tracker**: Detailed prior vaccination history collection
- **Print-Optimized Output**: Compact, professional printouts that fit on one page
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/herbicider/hayat_vac.git
   cd hayat_vac
   ```

2. **Open the application**
   - Simply open `vac.html` in any modern web browser
   - No server setup required - it's a standalone HTML application

3. **Start using**
   - Enter patient's date of birth and gender
   - Select desired vaccines from organized categories
   - Get personalized recommendations
   - Print professional reports

## 📋 Usage

### **For Patients**
1. Fill in your date of birth and gender
2. Browse vaccine categories and select vaccines of interest
3. For pneumonia vaccines, provide your vaccination history for better recommendations
4. Click "Get Recommendations" for age-appropriate suggestions
5. Use "Show Selected" to see your chosen vaccines
6. Print the results for your records

### **For Healthcare Providers**
- Use as a consultation tool during patient visits
- Help patients understand CDC-recommended vaccines
- Generate printable vaccine schedules
- Track pneumonia vaccination history efficiently

## 🏥 Pneumonia Vaccine Logic (CDC Option B)

The tool follows CDC pneumococcal vaccine guidelines with Option B preference:

| Prior Vaccines | Recommendation |
|---|---|
| **None** | PCV15 → PPSV23 (≥1 year later) |
| **PCV15 only** | PPSV23 (≥1 year after PCV15) |
| **PPSV23 only** | PCV15 (≥1 year after PPSV23) |
| **PCV13 only** | PCV20 or PCV21 (≥1 year after PCV13) |
| **Complete series** | No vaccines recommended |

## 🎨 Customization

### **Branding**
- Update colors in CSS variables to match your pharmacy branding
- Modify header text and contact information
- Customize footer links and location details

### **Vaccine List**
- Add or remove vaccines in the HTML structure
- Update age-based recommendations in JavaScript
- Modify vaccine categories as needed

### **Special Instructions**
- Customize the Yellow Fever alert for your workflow
- Add similar alerts for other special vaccines
- Modify contact information and locations

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No external dependencies
- **Responsive Design** - Works on all device sizes
- **Print Optimization** - Clean, compact printouts
- **Local Storage** - No data transmitted externally
- **Cross-Browser Compatible** - Supports all modern browsers

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-vaccine`)
3. Commit your changes (`git commit -am 'Add new vaccine type'`)
4. Push to the branch (`git push origin feature/new-vaccine`)
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏪 About Hayat Pharmacy

This tool was developed for Hayat Pharmacy to streamline vaccine consultations and improve patient education. 

**Contact Information:**
- Website: [hayatrx.com](https://www.hayatrx.com/)
- Locations: [Find a Location](https://www.hayatrx.com/locations/)
- Vaccine Services: [Learn More](https://www.hayatrx.com/health-services/vaccines/)

## 📞 Support

For technical issues or questions about this tool:
- Create an issue in this repository

For vaccine-related questions:
- Contact Hayat Pharmacy directly at your nearest location
- Walk-in vaccines available for ages 6+

---

**Disclaimer:** This tool provides general vaccine recommendations based on CDC guidelines. Always consult with a qualified healthcare provider for personalized medical advice.
