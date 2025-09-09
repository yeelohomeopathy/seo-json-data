# SEO JSON Data – Yeelo Homeopathy

This repository contains SEO-optimized JSON files for all villages and localities in Sohna, Gurgaon, Haryana.  

Each JSON file includes:
- Location name
- SEO title & meta description
- Keywords
- Store contact info
- Google Maps link

These files are used to generate local landing pages and integrate with Google Business Profile (GMB).

# Yeelo Homeopathy
Yeelo Homeopathy is a retail & wholesale homeopathic medicine store in Sohna, Gurgaon.  
Visit: [Yeelo Homeopathy Online Store](http://yeelohomeopathy.com) | [Shop Medicines](http://yeelohomeopathy.shop)


You are an AI agent working for Yeelo Homeopathy, a retail & wholesale homeopathy medicine store located at Berka Road, Dhunela, Sohna, Gurgaon. Your goal is to generate highly localized SEO landing pages for each location in Sohna and surrounding villages so that customers searching on Google Maps or Google Search can easily find Yeelo Homeopathy.

### Instructions:
1. Use this base business info:
   - Business Name: Yeelo Homeopathy
   - Type: Retail & Wholesale Homeopathic Medicine Store
   - Address: Near Bikaner Sweets, Berka Road, Dhunela, Sohna, Gurgaon, Haryana
   - Phone: +91 8478019973
   - Website: https://yeelohomeopathy.com
   - Services: Homeopathy medicines, doctor consultation support, bulk supply to doctors/pharmacies, retail and online orders.
   - Keywords: Homeopathy Store in Sohna, Buy Homeopathy Medicines Gurgaon, Homeopathic Doctor Support Sohna.

2. Generate an SEO landing page for each location in this list:
   Abhepur, Alipur, Badshahpur, Bai Khera, Balola, Baluda, Bandhwari, Bedhwaka, Behlpa, Berka, Bhogpur, Bhondsi, Bhrempur, Bilaka, Chuharpur, Damdma, Darbaripur, Daula, Dhunela, Garhi Bazidpur, Ghamroj, Ghangola, Ghata, Gual Pahari, Hajipur, Harchandpur, Hariahera, Hassanpur, Isaka, Jolahaka, Kadarpur, Karnki, Khaika, Kharki Dola, Kharoda, Khatrika, Kherla, Kherli Lala, Khuntpuri, Kuliaka, Lakhuwas, Loh Singhani, Lohatki, Mahendwara, Mandawar, Mohammadpur Gujar, Nimot, Nunera, Rahaka, Raipur, Raisena, Ranika Singhola, Ratika Noabad, Rethoj, Sahjawas, Sakatpur, Sampki Nagli, Sancholi, Saramathla, Satlaka, Shikohpur, Silani, Siraska, Sohna, Tethar, Tolni, Ulhawas, Zakupur.

3. For each location page include:
   - **H1 Title**: "Homeopathy Medicine Store in [Location], Sohna – Yeelo Homeopathy"
   - **Intro Paragraph**: Explain that Yeelo Homeopathy serves this location with homeopathy medicines, delivery, and doctor support. Mention Sohna and Gurgaon for SEO relevance.
   - **Local Focus Section**: Talk about how residents of [Location] can easily access Yeelo Homeopathy’s store (offline + online). Mention Google Maps directions to Sohna store.
   - **Services Section**: Retail store, online ordering, doctor consultation, bulk supply for doctors/pharmacies.
   - **Contact CTA**: Phone number, address, Google Maps link.
   - **SEO Keywords**: Homeopathy Store in [Location], Buy Homeopathy Medicines [Location], Homeopathic Doctor Sohna, Gurgaon Homeopathy.

4. Output format:
   - One page per location
   - HTML or Markdown with headings, meta description, and structured data (LocalBusiness schema).

5. Add Internal Links:
   - Link to "All Locations" page (master list).
   - Link to Yeelo Homeopathy homepage.

### Goal:
Ensure that when users in Sohna or its villages search "homeopathy store near me" or "buy homeopathy medicines [village name]", these landing pages rank on Google and connect to Yeelo Homeopathy’s GMB profile.

{
  "location": "Sohna",
  "title": "Homeopathy Medicine Store in Sohna – Yeelo Homeopathy",
  "meta_description": "Yeelo Homeopathy in Sohna, Gurgaon offers all top homeopathy brands, doctor consultation, and medicine delivery.",
  "keywords": ["homeopathy store Sohna", "buy homeopathy medicines Sohna"],
  "phone": "+91 8478019973",
  "address": "Near Bikaner Sweets, Berka Road, Dhunela, Sohna, Gurgaon, Haryana"
}

# Homeopathy Store in {{location}}, Sohna – Yeelo Homeopathy

Yeelo Homeopathy proudly serves **{{location}}** with trusted homeopathy medicines.  
📍 Visit us: {{address}}  
📞 Call: {{phone}}  

## Why Choose Us?
- 100% Genuine Homeopathy Medicines
- All Top Brands: SBL, Schwabe, Bakson’s, Allen’s
- Doctor Support Available
- Bulk Supply for Doctors & Pharmacies

[Google Maps Directions]({{maps_link}})

{
  "@context": "https://schema.org",
  "@type": "Pharmacy",
  "name": "Yeelo Homeopathy - Sohna",
  "address": {
    "streetAddress": "Berka Road, Dhunela, Sohna",
    "addressLocality": "Sohna",
    "addressRegion": "Haryana",
    "postalCode": "122103",
    "addressCountry": "IN"
  },
  "telephone": "+91-8478019973",
  "url": "https://yeelohomeopathy.com/haryana/gurgaon/sohna/"
}

folder structure seo-json-data/ with one JSON file per village.

Each JSON file will contain:

Location name

SEO title

Meta description

Keywords

Store phone

Store address (your Yeelo Homeopathy Sohna address)

Google Maps link

This way, the files are ready for your GMB + website landing page integration.

📂 Example Folder Structure
seo-json-data/
├── abhepur.json
├── alipur.json
├── badshahpur-tethar.json
├── bai-khera.json
├── balola.json
├── baluda.json
├── bandhwari.json
...
├── ulhawas.json
└── zakupur.json

📄 Example JSON File (seo-json-data/abhepur.json)
{
  "location": "Abhepur",
  "title": "Homeopathy Medicine Store in Abhepur, Sohna – Yeelo Homeopathy",
  "meta_description": "Yeelo Homeopathy serves Abhepur village in Sohna, Gurgaon with trusted homeopathy medicines. Visit our store near Bikaner Sweets, Berka Road, Dhunela for genuine homeopathy products.",
  "keywords": ["homeopathy Abhepur", "buy homeopathy medicines Abhepur", "Sohna pharmacy Abhepur"],
  "phone": "+91 8478019973",
  "address": "Yeelo Homeopathy, Near Bikaner Sweets, Berka Road, Dhunela, Sohna, Gurgaon, Haryana - 122103",
  "maps_link": "https://maps.app.goo.gl/i52VSsSyuehH8x2F6"
}


Each file will follow the same structure, only changing the location, title, meta_description, and keywords.
