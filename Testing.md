# Test Record — Where Does Our Water Go?

**Published page:** https://ahattar10.github.io/-ASSESSMENT-Data-Story-Starter/


All tests performed in [Browser name, e.g. Chrome] on [OS, e.g. Windows/macOS].

---

## 1. HTML & CSS Validation
Validated with the W3C Validator. No errors.
- HTML: ![HTML validation](screenshots/HTML%20validation.png)
- CSS: ![CSS validation](screenshots/CSS%20validation.png)

## 2-4. Viewport Checks (320px / 768px / 1280px)
Resized in responsive mode to confirm layout, figures, table, and SVG stay usable with no horizontal overflow.
- 320px: ![320px](screenshots/320px.png)
- 768px: ![768px](screenshots/768px.png)
- 1280px: ![1280px](screenshots/1280%20px.png)

## 5. 200% Zoom / Reflow
Zoomed the page to 200%; content reflowed without cutting off text or losing access.
![200% zoom](screenshots/200%25.png)

## 6. Keyboard Access + Overflowing Table Region
Navigated with the Tab key through all interactive elements; the data table's scrollable region is reachable and scrollable via keyboard.
![Keyboard / table region](screenshots/keyboard.png)

## 7. Accessibility-Tree Inspection (figure, table, SVG)
Inspected the accessibility tree; each figure, the table, and the SVG expose a correct accessible name and structure.
![Accessibility tree](screenshots/accessablity%20tree.png)

## 8. Image-Disabled Review
Disabled images; alternative text and figure captions preserve the meaning of each figure.
![Images disabled](screenshots/image%20disable.png)
![Images disabled 2](screenshots/image%20disable%20%232.png)

---

## Source-to-Page Spot Check (data verification)
Three or more values cross-checked against the cited U.S. EPA WaterSense fact sheet:
- 400 gallons / family of four / day — verified
- Toilet at about 27% of indoor use (26.7%) — verified
- Running toilet wastes ~200 gallons/day — verified
- Showerhead ~2.5 gal/min; faucet ~2 gal/min — verified
![Source spot check](screenshots/source%20spot%20check.png)