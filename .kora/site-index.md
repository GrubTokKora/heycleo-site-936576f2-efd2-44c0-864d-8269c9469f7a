# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Pooch Professional Grooming Services – Dog Grooming in Altona North
purpose: Home page for a dog grooming salon in Altona North, featuring services, gallery, reviews, team, FAQ, and booking options.
sections:
- `#hero` — Hero banner with introductory messaging and call to action
- `#offerings` "Our grooming services" — Featured dog grooming services with starting prices: Full Groom, Beauty Bath, Bath & Tidy Up, Puppy's First Trim, De-shed Treatment, Nail Clip
- `#gallery` "Happy pups, stunning results" — Photo gallery of groomed dogs
- `#story` "We're dog people, through and through" — Business background story and trust points
- `#reviews` "Dogs leave happy. Owners come back." — Customer reviews and testimonials: Laura M, Julianne Slevison, Rachel McDonald, Mardi, Dom Ling
- `#team` "The people behind the pampering" — Staff profiles and team biographies: Alisha, Jane, Irene
- `#offers` — Promotional offers and announcements
- `#faq` "Questions we hear all the time" — Frequently asked questions and answers about grooming: How often should I get my dog groomed?, How long will my dog's groom take?, My dog is nervous about grooming — is that okay?, What products do you use?, What should I do before bringing my dog in?, How do I book an appointment?
- `#hours_location` — Business address, contact details, and opening hours table
- `#cta` "Ready to treat your pup?" — Call-to-action block for booking
also: The weekly opening hours appear in both the visible hours section and the JSON-LD LocalBusiness and FAQPage markup.
also: Customer reviews and ratings appear in both the visible reviews section and the JSON-LD LocalBusiness markup.

## 404.html → /404
title: Pooch Professional Grooming Services – Page Not Found
purpose: Display a 404 error message when a requested page cannot be found.
sections:
- Error message and navigation links: Back to home, See our services

## about.html → /about
title: About Us | Pooch Professional Grooming – Altona North
purpose: Provide information about the business, its history, team members, customer reviews, and special offers.
sections:
- `#story` — hero and business story: Altona North, Book an appointment, See our services
- `#reviews` — customer reviews: Laura M, Julianne Slevison, Rachel McDonald, Mardi, Dom Ling
- `#team` — team member profiles: Alisha, Jane, Irene
- `#offers` — special offers and promotions: 15% off for Pensioners, Spring is here — fresh grooms now booking, Book online now!
- `#cta` — call to action: Altona North, Book online now!, Get a free quote
also: The meta description and page title appear in the head tag and the JSON-LD structured data block.

## booking.html → /booking
title: Book an Appointment | Pooch Professional Grooming – Altona North
purpose: Online booking and quote request page for dog grooming services
sections:
- `#hero` "Book your pup's next pamper session" — Hero band with online booking link: Online booking, Book online now!, See our services →
- `#booking_ways` "However you prefer" — Three booking options: online, phone, and email: Book online, Call us, Email us, Book online now!
- `#booking_widget` "Select a time that suits" — Online booking software widget integration card: Choose your appointment, Book online with Shortcuts Software, Open booking system
- `#what_to_expect` "What to expect" — Four step guide for first-time visitors and preparation checklist: Book your slot, Drop off your pup, We work our magic, Pick up a happy pup
- `#quote_form` "Get a free quote" — Custom quote request form and service selector: Full Groom, Beauty Bath, Bath & Tidy Up, Puppy's First Trim, De-shed Treatment, Nail Clip, Not sure — need advice, Send my quote request
- `#faq` "Common questions" — Frequently asked questions accordion: How do I book an appointment?, How long will my dog's groom take?, My dog is nervous about grooming — is that okay?, What should I bring?, What's included in a full groom?, How often should I book a groom?
- `#cta` "Ready to treat your pup?" — Call to action banner with booking and quote links: Book online now!, Get a free quote

## gallery.html → /gallery
title: Gallery | Pooch Professional Grooming – Altona North
purpose: Show photos of completed dog grooming transformations at the Altona North salon
sections:
- `#gallery` — photo gallery and trust indicators: Full groom, Beauty bath, Bath & tidy up
also: The business name and gallery name appear in the JSON-LD schema block and the page title.

## pooch-care.html → /pooch-care
title: Pooch Care | Dog Care Tips & Guides | Pooch Professional Grooming
purpose: Provide dog care tips, seasonal grooming guides, and coat maintenance advice for dog owners.
sections:
- `#care-hero` "Pooch Care — grooming tips & seasonal guides" — Hero introduction
- `#articles` "Seasonal guides & care tips" — Care articles and guides: Protecting Your Dog's Paws This Winter: A Complete Guide
- `#between-grooms` "How to care for your dog's coat between visits" — Coat care steps and advice
- `#groom-frequency` "How often should my dog be groomed?" — Grooming frequency table by coat type: Curly & wavy coats, Long silky coats, Double coats, Wiry & harsh coats, Short smooth coats
- `#quick-tips` "Good to know" — Quick reference care cards
- `#care-faq` "Coat care questions we hear all the time" — Frequently asked questions
- `#care-cta` "Ready to book your pup in?" — Call to action block

## services.html → /services
title: Services & Pricing | Pooch Professional Grooming – Altona North
purpose: Services and pricing guide with interactive quote form for a dog grooming salon.
sections:
- `#hero` "Services & pricing" — Hero introduction: Pensioners

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — business contact details, address, email, phone number, and website URL for Pooch Professional Grooming Services - Altona North: Pooch Professional Grooming Services - Altona North, 3 Misten Avenue, Altona North  [content]
- `robots.txt` — 45 bytes — too small to hold content
- `sitemap.xml` — 160 bytes — too small to hold content

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
