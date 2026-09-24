<a href="https://halocity.svilenkovic.rs/"><img src="media/cover.jpg" alt="Halo City Leskovac, home page on a laptop and a phone" width="100%"></a>

# Halo City Leskovac

Five-page site for a phone shop and repair service in Leskovac, where every call to action is a phone call or a Viber message.

**[halocity.svilenkovic.rs](https://halocity.svilenkovic.rs/)** · [Case study (in Serbian)](https://svilenkovic.com/radovi/halo-city-leskovac) · [Srpski](README.sr.md)

> [!NOTE]
> Client project. The source code belongs to the client and stays in a private repository. This page describes what I built and how.

<table>
  <tr><td><b>Client</b></td><td>Halo City</td></tr>
  <tr><td><b>Industry</b></td><td>Mobile phone sales and repair</td></tr>
  <tr><td><b>Location</b></td><td>Leskovac, Serbia</td></tr>
  <tr><td><b>Type</b></td><td>Multi-page website</td></tr>
  <tr><td><b>My role</b></td><td>Design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>Next.js 16, React 19, Tailwind 4, TypeScript</td></tr>
</table>

## About the project

Halo City has sold and repaired mobile phones in the centre of Leskovac since 2014, and customers also come in from Vlasotince, Lebane, Bojnik and Medveđa. Buying a phone and fixing a cracked screen are two different searches, and one long page could only compete for one of them. So the site has five pages, with products and service each getting their own title, description and address.

Stock and prices change too often for a website, so the site publishes neither and says so. Instead it tells people what to send before they come in: brand, exact model, memory and colour for a purchase, or, for a repair, the model, the symptoms, whether the phone still turns on and whether it was dropped or got wet. The Viber button opens a message with that template already started, different on each page. The service page also has a short checklist for handing a phone in: back up your data, take out the memory card and never send the passcode in a message.

## What I built

- Five pages plus a privacy policy: home, products, service, about and contact
- Phone and Viber on every screen and no contact form, because nobody behind the counter watches an inbox during the day
- Business details on the about page matched to the public business register
- The Google rating shown together with the date it was last checked
- A consent bug fixed: the banner saved consent under one name and the analytics read another, so returning visitors were never counted
- A move to a new host with one-hop 301 redirects that kept every path, and the same plan ready for the shop's own domain

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 96 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, lab test of the live site, September 2026. Security headers: 6 of 6. HTML validator: no errors. axe accessibility check: no violations. Structured data: `MobilePhoneStore`, `Organization`.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Halo City Leskovac, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Halo City Leskovac, home page on a phone"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Sales, repairs and accessories, then the banner &quot;Radnja kojoj Leskovac veruje već 12 godina&quot;">
<sub>Sales, repairs and accessories, then the banner "Radnja kojoj Leskovac veruje već 12 godina"</sub>

<img src="media/inner-2.webp" alt="Customer reviews from Google Maps, with the location and opening hours below">
<sub>Customer reviews from Google Maps, with the location and opening hours below</sub>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
