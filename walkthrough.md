# Walkthrough - Hero Banner Section

## Summary
Created a pixel-perfect hero section for the "About Us" page matching the exact CSS specifications and UI reference image provided.

## Specifications Implemented
- **Width:** `100%`, max-width `1920px`
- **Height:** `691px`
- **Angle:** `0deg`
- **Opacity:** `1`
- **Border Radius:** `border-bottom-right-radius: 60px;` and `border-bottom-left-radius: 60px;`
- **Background:** High-resolution office background (`banner.jpg`) with depth gradient overlay.

## Components Built
1. **Top Maroon Bar:**
   - Exact Figma Dimensions: `1920 × 60 Hug` (`min-height: 60px;`)
   - Phone contact link `(021) 111-TAKAFUL(825-238)` with SVG phone icon
   - Secondary links (Complain Form, Purchase Policy, Branch Locator, Careers, Contact Us)
   - Day/night theme switch toggle
   - Language selector pill with circular Pakistan flag icon (`flag-pk.png` + `EN`)
   - Customer Portal link with avatar outline
   - Dual accent trim lines placed cleanly outside the maroon bar (zero red bleeding below the black line):
     - Upper yellow/golden trim line (`.gold-strip`: `height: 2.5px; background: linear-gradient(90deg, #b8860b 0%, #ffd700 50%, #b8860b 100%);`)
     - Lower solid black divider line (`.nav-black-strip`: `height: 7px; background: #000000;`) - calibrated to a bold, prominent 7px thickness for strong division beneath the gold accent line
2. **Glassmorphic Floating Navbar:**
   - Exact Alignment: Perfectly aligned to start horizontally at the exact same line as the upper navbar content (`.top-bar-inner` phone contact `(021) 111-TAKAFUL(825-238)`), utilizing `max-width: 1820px; margin: 0 auto; padding: 0 36px 0;` (and matching responsive breakpoint paddings `24px` and `16px`) so the left edge of the glass navbar aligns with zero pixel offset across all resolutions.
   - Exact Dimensions & Styling: `height: 86px; border-radius: 20px; justify-content: space-between; angle: 0deg; opacity: 1; padding: 15px 20px;`
   - Zero top space above the glass navbar (`padding-top: 0;`), sitting completely flush directly below the black line
   - Blur effect (`backdrop-filter: blur(28px);`) with semi-transparent background and border
   - Brand logo emblem image (`logo.png`)
   - Brand logo text with exact dimensions (`width: 120.45px; height: 39.33px; opacity: 1; top: 23.45px; left: 78.11px;`) and white typography
   - Navigation menu links with active state indicator
   - "Get Quote" CTA button with exact Figma dimensions and updated typography: `width: 156px; height: 55px; angle: 0deg; opacity: 1; gap: 24px; font-family: Gill Sans MT; font-weight: 400; font-size: 18px; line-height: 100%; letter-spacing: -2%; text-align: center;`, with customized enclosed arrow circle (`width: 45px; height: 45px; border-radius: 30px; border: 1px solid #DDDDDD;`), and smooth hover interactions
3. **Hero Centerpiece:**
   - Prominent title `About Us` centered in the hero banner styled with exact Figma typography: `font-family: SF Pro; font-weight: 510; font-size: 60px; line-height: 70px; letter-spacing: -3px; text-align: center; color: #ffffff;`
4. **Partner in Shariah-Compliant Protection Section:**
   - Centered title `Your trusted partner in Shariah-Compliant Protection` styled with exact Figma specs: `SF Pro; font-weight: 510; font-size: 60px; line-height: 70px; letter-spacing: -2px; text-align: center; background: linear-gradient(90deg, #000000 0%, #A31F37 100%); -webkit-background-clip: text;`
   - Group subtitle styled with exact Figma Heading 2 specs (`Inter; font-weight: 500; font-size: 24px; line-height: 28px; letter-spacing: -4%; text-align: center;`) and company heading `Pak-Qatar General Takaful Limited` styled with gradient (`background: linear-gradient(90deg, #000000 0%, #A31F37 100%); -webkit-background-clip: text; font-size: 28px; font-weight: 700;`)
   - Narrative paragraphs styled with exact Figma paragraph specs: `Inter; font-weight: 400; font-size: 20px; line-height: 28px; letter-spacing: -5%; text-align: center;`
   - "Read More" maroon pill CTA button styled to match Figma mockup (`height: 55px; border-radius: 40px; font-family: Gill Sans MT; font-weight: 400; font-size: 18px; line-height: 100%; letter-spacing: -2%; padding: 0 5px 0 24px; gap: 18px;`) with enclosed circular arrow badge (`width: 45px; height: 45px; border-radius: 30px; border: 1px solid #DDDDDD; background: rgba(255, 255, 255, 0.18);`) and smooth hover interactions
5. **Support Assistant Mascot Widget:**
   - Circular widget with green glowing aura rings and mascot avatar (`chatbot-avatar.png`)
   - Anchored directly to the Shariah-Compliant Protection section (`position: absolute; right: 48px; top: 60px;`) so it stays stuck in place within this section as designed, without following the scroll across the rest of the page.
6. **Mission & Key Milestones Section:**
   - Soft mint-to-white gradient background matching the UI mockup
   - Mission Card featuring stacked hands photograph (`mission.jpg`) with dark gradient overlay
   - "Our Mission" title styled with exact Figma specs: `SF Pro`, font-weight 510, font-size 40px, line-height 100%, letter-spacing -5%
   - Mission statement narrative paragraph styled with exact Figma specs: `Inter`, font-weight 400, font-size 18px, line-height 28px, letter-spacing -4%
   - Carousel navigation circle buttons
   - 4-card metrics grid (`2007`, `19 Branches`, `A+ Rating`, `100%`) styled with exact Figma specs: `max-width: 390px; height: 236px; border-radius: 20px; padding: 30px; background: #FFFFFF; border: 1px solid #EEEEEE; justify-content: space-between;`
7. **Our Values Section:**
   - Section header: `Our Values` with heading typography (`SF Pro`, 510 weight, 40px, -5% tracking, maroon highlight on "Values") and right-aligned subtitle paragraph (`Inter`, 18px, line-height 26px, -5% tracking)
   - 3x2 grid of 6 value cards (`Excellence`, `Integrity`, `Commitment`, `Innovation`, `Teamwork`, `Responsibility`)
   - High-res cropped maroon outline icons for each card (`val-star.png`, `val-integrity.png`, `val-commitment.png`, `val-innovation.png`, `val-teamwork.png`, `val-responsibility.png`)
   - Interactive top-right diagonal arrow button (`↗`) and smooth hover elevation on every card
8. **Board Of Directors Section:**
   - Section header: `Board Of Directors` styled with exact Figma specs: `SF Pro`, font-weight 510, font-size 60px, line-height 70px, letter-spacing -2px, text-align center, with "Directors" highlighted in brand maroon
   - Two-column interactive layout:
     - Left column: 9 director selection tabs with serif font and active maroon pill highlight
     - Right column: Detail card featuring the director's full designation styled with exact Figma specs (`SF Pro; font-weight: 510; font-size: 40px; line-height: 45px; letter-spacing: -1.5px;`) and biography paragraphs (`Inter; font-weight: 400; font-size: 20px; line-height: 28px; letter-spacing: -5%;`)
   - Interactive tab-switching JavaScript dynamically updating director information on click
9. **Ready to Protect What Matters Most Section:**
   - Large banner card with `border-radius: 28px;`, dual radial ambient gradients (warm gold & soft rose), and dual decorative wave curves styled with exact Figma specs: Upper (`width: 2089px; height: 209px; border: 42px solid #A31F37; opacity: 0.1; angle: 0deg;`) and Lower (`width: 2089px; height: 221px; border: 42px solid #A31F37; opacity: 0.1; angle: 0deg;`)
   - Left column: Headline `Ready to Protect What Matters Most?` styled with exact Figma specs (`SF Pro; font-weight: 510; font-size: 60px; line-height: 65px; letter-spacing: -2px; background: linear-gradient(90deg, #000000 0%, #A31F37 100%); -webkit-background-clip: text;`) and narrative paragraph (`Inter; font-weight: 400; font-size: 20px; line-height: 28px; letter-spacing: -5%;`)
   - Right column: Clean rounded container (`border-radius: 22px;`) framing the high-resolution car & home photo (`protect.jpg`)
   - Responsive multi-device layout
10. **Official Site Footer:**
   - Left column: Enhanced company vertical brand logo (`footer-logo.png`, height 64px) and unified regulatory logos (`jamapunji.png`, `fio.png`, `secp.png`) calibrated to exact 100% pixel-perfect flush left alignment (all 4 logos starting precisely at the identical left edge line) and uniform ~171-172px width for JamaPunji, FIO, and SECP matching reference image `media_1793706411188_f478c47e.png`.
   - Proportional layout: Container calibrated to `max-width: 1120px` with 580px links wrapper (`grid-template-columns: 120px 220px 160px;`), establishing the exact 28% void gap ratio and horizontal harmony between logos and link columns.
   - Top links row: 3 organized columns (Quick Links with active maroon "About Us", Individual Takaful with wrapped "Complaints in Respect of Takaful<br>Membership", Corporate Takaful with "Liability Tankful").
   - Bottom row: Official Karachi headquarters address, contact telephone/fax lines, and "Join Us Now" compact green-bordered social media buttons strictly grid-aligned directly under Corporate Takaful (364px + 160px).
   - Bottom copyright strip: `Copyright © 2026 Pak-Qatar Takaful Group. Managed by Sidat Technologies & Digital` with subtle `#eeeeee` top divider line

## File Changes
- [flag-pk.png](file:///c:/Nirmal2026/pqgtl/About-us/flag-pk.png): Official circular Pakistan national flag icon for language selector.
- [logo.png](file:///c:/Nirmal2026/pqgtl/About-us/logo.png): Real brand logo mark image with transparency.
- [chatbot-avatar.png](file:///c:/Nirmal2026/pqgtl/About-us/chatbot-avatar.png): High-resolution transparent 3D mascot avatar image.
- [mission.jpg](file:///c:/Nirmal2026/pqgtl/About-us/mission.jpg): High-resolution stacked hands photo for the mission card.
- [protect.jpg](file:///c:/Nirmal2026/pqgtl/About-us/protect.jpg): High-resolution car & home photograph for the Ready to Protect card.
- [footer-logo.png](file:///c:/Nirmal2026/pqgtl/About-us/footer-logo.png), [jamapunji.png](file:///c:/Nirmal2026/pqgtl/About-us/jamapunji.png), [fio.png](file:///c:/Nirmal2026/pqgtl/About-us/fio.png), [secp.png](file:///c:/Nirmal2026/pqgtl/About-us/secp.png): Official company and regulatory logos for footer.
- [val-star.png](file:///c:/Nirmal2026/pqgtl/About-us/val-star.png), [val-integrity.png](file:///c:/Nirmal2026/pqgtl/About-us/val-integrity.png), [val-commitment.png](file:///c:/Nirmal2026/pqgtl/About-us/val-commitment.png), [val-innovation.png](file:///c:/Nirmal2026/pqgtl/About-us/val-innovation.png), [val-teamwork.png](file:///c:/Nirmal2026/pqgtl/About-us/val-teamwork.png), [val-responsibility.png](file:///c:/Nirmal2026/pqgtl/About-us/val-responsibility.png): High-res cropped values icons.
- [index.html](file:///c:/Nirmal2026/pqgtl/About-us/index.html): Semantic footer markup with regulatory logos, navigation, contact details, social links, and copyright bar matching the reference mockup.
- [style.css](file:///c:/Nirmal2026/pqgtl/About-us/style.css): Pixel-perfect styling for footer layout: configured `.footer-container` with `align-items: stretch` and `.footer-logos-col` with `justify-content: space-between`, ensuring the left logo column starts exactly flush at the top with the "Quick Links" heading (0.0px delta) and ends flush at the bottom with the contact address FAX line (0.0px delta). Preserves complete layout integrity across all other sections.

## Manual Verification Steps
1. Open `c:\Nirmal2026\pqgtl\About-us\index.html` in any web browser.
2. Verify dimensions (1920px width limit, 691px height hero banner).
3. Verify brand logo emblem (`logo.png`) and white "PAK-QATAR GENERAL TAKAFUL" text in the glass navbar.
4. Verify top maroon bar, floating navigation bar, and cleanly centered "About Us" title.
5. Verify the Shariah-Compliant Protection section with exact text, typography, and "Read More" button.
6. Verify the Mission & Key Milestones section with exact box heading typography (`40px`, SF Pro, 510 weight) and paragraph typography (`18px / 28px`, Inter, -4% tracking).
7. Verify the Our Values section with "Our Values" title (SF Pro 40px, -5% tracking), intro paragraph (Inter 18px / 26px), and 6 cards with respective maroon icons and up-right arrow buttons.
8. Verify the Board Of Directors section with centered "Board Of Directors" title (SF Pro 60px / 70px, -2px tracking), left tab list, and right detail card with interactive switching.
9. Verify the "Ready to Protect What Matters Most?" banner card with the car & home image (`protect.jpg`) and decorative background curves.
10. Scroll down to verify the Site Footer: the left logos stack starts flush with "Quick Links" and ends flush with the contact address bottom, with even distribution.
11. Verify the floating chatbot assistant widget anchored cleanly on the Shariah protection section.

