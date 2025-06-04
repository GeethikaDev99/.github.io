# 🗺️ Geospatial Delivery App (Swiggy-style Prototype)

A geolocation-enabled Power App used to simulate location tracking and delivery tagging — inspired by food delivery apps like *Swiggy*. This was built and tested in my own Microsoft 365 tenant and integrated into a Hackathon project to showcase how items can be linked to real-world coordinates.

---

## 🚀 Features

- 📍 *Save and Track Locations* using latitude/longitude
- 🗺️ Display saved coordinates visually on an interactive map (HTML control)
- 📦 Link item entries to specific locations during checkout
- 🔁 Use case simulation for "Send to My Location" type actions
- 📱 Fully mobile-optimized for testing in the field
- 🔒 Role-based access for different users

---

## 🧪 Use Case

This app was developed as part of a *Hackathon project* where users could:
- Add items (like products or requests)
- Set their current location or a target delivery address
- View and track those saved locations on an embedded map

While it’s not built in 3D or real-time routing format, it effectively demonstrates *location-aware capabilities inside Power Apps* using available connectors and HTML embedding.

---

## 🔧 How It Works

| Feature                    | Implementation Detail                      |
|---------------------------|---------------------------------------------|
| 📍 Location Capture        | Location.Latitude, Location.Longitude |
| 🗺️ Map Display             | Embedded Bing/Google Maps via HTML Text    |
| 📤 Save with Item          | Patch() to SharePoint/Dataverse          |
| 👥 Role Security           | User().Email + conditional screens        |

---

## 📷 Screenshots

You can add screenshots or a GIF of the app here.

```markdown
![Item Entry with Location](./Media/item-entry-location.png)
![Map View](./Media/map-view.png)
