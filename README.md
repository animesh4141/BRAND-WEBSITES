# Saraswati Bal Niketan School Website - Setup Instructions

## 📸 Image Setup Instructions

### Gallery Images (School Photos)
Place your school photos in the `images/` folder with these exact names:

1. **school-building.jpg** - Main school building exterior
2. **classroom.jpg** - Smart classroom with students
3. **library.jpg** - School library
4. **lab.jpg** - Science laboratory
5. **computer-lab.jpg** - Computer lab
6. **playground.jpg** - School playground/sports ground
7. **auditorium.jpg** - School auditorium
8. **campus.jpg** - Campus view

### Sports Images
Add these sports-related photos in the `images/` folder:

1. **cricket.jpg** - Cricket field or students playing cricket
2. **football.jpg** - Football ground or football activity
3. **basketball.jpg** - Basketball court
4. **badminton.jpg** - Badminton court
5. **athletics.jpg** - Athletics track or running
6. **volleyball.jpg** - Volleyball court
7. **table-tennis.jpg** - Table tennis facility
8. **yoga.jpg** - Yoga or fitness session

### Image Requirements:
- **Recommended Size**: 1200x800 pixels (landscape orientation)
- **Format**: JPG or PNG
- **File Size**: Keep under 500KB for faster loading
- **Quality**: High resolution but optimized for web

**Note**: If images are not added, placeholder images will be shown automatically.

---

## 🗺️ Google Map Location Setup

### Current Location:
The map is currently set to **Kankarbagh, Patna, Bihar**

### To Update with Your Exact School Location:

1. **Get Your School's Coordinates**:
   - Open Google Maps: https://maps.google.com
   - Search for your school address
   - Right-click on your school location
   - Click on the coordinates (e.g., 25.594095, 85.172179)
   - Copy the coordinates

2. **Get Google Maps Embed Code**:
   - Go to Google Maps
   - Search for your school
   - Click "Share" button
   - Click "Embed a map"
   - Copy the iframe code
   - Replace the iframe in `index.html` (line ~823)

3. **Manual Update**:
   Open `index.html` and find this section (around line 823):
   ```html
   <iframe 
       src="https://www.google.com/maps/embed?pb=!1m18!1m12!..."
   ```
   Replace the entire iframe with your copied embed code from Google Maps.

### Alternative - Update Coordinates Only:
In the iframe `src`, find and replace these values:
- Latitude: `25.594095` (replace with your latitude)
- Longitude: `85.172179` (replace with your longitude)

---

## 🚀 How to Use This Website

### Local Testing:
1. Extract all files to a folder
2. Make sure these files are in the same folder:
   - `index.html`
   - `style.css`
   - `script.js`
   - `images/` folder with your photos

3. Double-click `index.html` to open in browser

### Upload to Web Hosting:
1. Upload all files to your web hosting:
   - index.html (main file)
   - style.css
   - script.js
   - images/ folder

2. Make sure folder structure is maintained:
   ```
   your-website/
   ├── index.html
   ├── style.css
   ├── script.js
   └── images/
       ├── school-building.jpg
       ├── classroom.jpg
       ├── cricket.jpg
       └── ...other images
   ```

---

## 📝 Customization Tips

### Change School Name & Details:
- Open `index.html`
- Search and replace "Saraswati Bal Niketan School" with your school name
- Update contact details (address, phone, email)
- Update all text content as per your school

### Change Colors:
- Open `style.css`
- Find the `:root` section (top of file)
- Modify color variables:
  - `--primary-color`: Main blue color
  - `--accent-color`: Orange/gold color

### Update Contact Information:
Find the Contact section in `index.html` and update:
- Address
- Phone numbers
- Email addresses
- Working hours

---

## 🎨 Features Included

✅ Responsive design (works on mobile, tablet, desktop)
✅ Home page with hero section
✅ About School section
✅ About Saraswati Bal Niketan Trust section
✅ Photo Gallery
✅ Sports Section with achievements
✅ Admissions with guidelines and fee structure
✅ Contact form with validation
✅ Google Maps integration
✅ Mobile-friendly navigation
✅ Smooth scrolling
✅ Professional animations

---

## ⚠️ Important Notes

1. **Images**: Add your own school photos for best results
2. **Map**: Update with your exact school location
3. **Content**: Customize all text content
4. **Testing**: Test on different devices before going live
5. **Backup**: Keep a backup of your customized files

---

## 📞 Support

If you face any issues:
1. Check that all files are in the correct folder
2. Make sure image names match exactly
3. Verify the map iframe code is correct
4. Clear browser cache and reload

---

**Website Created for Saraswati Bal Niketan School**  
*Professional, Modern, and Mobile-Responsive Design*

