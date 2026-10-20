## User Stories – Hair by Lydia

### 1. Clear next step for consultation services
As a prospective client looking at a service that needs a consultation,  
I want a clear next step that takes me to the enquiry form,  
so that I know exactly how to start the process without guessing.

**Acceptance criteria**
- Given I am on a service page that requires consultation, when I look for the call-to-action, then I see a clear link or button that leads to the contact/enquiry form.
- The wording makes it obvious this is a request for a consultation, not an instant booking.

### 2. Keyboard- and touch-accessible image interactions
As a user who navigates with a keyboard or uses a touch device,  
I want image interactions (gallery, lightbox, or zoom) to be fully usable without a mouse,  
so that I can view the work without being locked out by the interface.

**Acceptance criteria**
- All interactive image controls can be reached and activated with the keyboard alone.
- Touch targets are large enough and work on mobile (no hover-only behaviour).
- Focus is visible and the interaction can be dismissed with Escape or an equivalent.

### 3. Helpful feedback when form submission fails
As a prospective client submitting an enquiry,  
I want clear feedback if the form fails to send, plus a way to try again or use another contact method,  
so that I am not left wondering whether Lydia received my message.

**Acceptance criteria**
- Given the form submission fails, when the error occurs, then a clear message appears explaining what went wrong.
- The user is offered a retry option and at least one alternative (e.g. email or phone).
- The form data is not silently lost.

### 4. Accessible indication of the current page
As a user who relies on screen readers or keyboard navigation,  
I want the current page to be clearly indicated in the navigation,  
so that I always know where I am in the site.

**Acceptance criteria**
- The current page is marked both visually (e.g. different style) and programmatically (aria-current="page" or equivalent).
- The indication works for every page that appears in the main navigation.

### 5. Understanding the form is an enquiry, not a booking
As a prospective client,  
I want to clearly understand that the form is a request for a consultation or availability check rather than an instant booking,  
so that I don’t expect a confirmed appointment and know I need to wait for Lydia’s reply.

**Acceptance criteria**
- The form heading and button text make it clear this is an enquiry.
- The success message after submission says Lydia will reply and does not say an appointment is confirmed.

### 6. Seeing services and prices clearly
As a prospective client,  
I want to see a clear list of services and their prices,  
so that I can decide whether the salon is within my budget before I enquire.

**Acceptance criteria**
- Services are grouped in a way that is easy to scan.
- Prices (or price ranges) are visible without having to contact Lydia first.
- Any service that needs a consultation is clearly marked.

### 7. Finding contact information easily
As a prospective client,  
I want to find Lydia’s contact details quickly,  
so that I can get in touch by my preferred method if I don’t want to use the form.

**Acceptance criteria**
- Phone number and email (or other contact methods) are easy to find on every page or in a consistent place.
- The contact information is also available on the contact/enquiry page itself.

### 8. Viewing Lydia’s work / portfolio
As a prospective client,  
I want to see examples of Lydia’s previous work,  
so that I can judge whether her style matches what I’m looking for.

**Acceptance criteria**
- There is a gallery or portfolio section with clear, good-quality images.
- Images have meaningful alt text.
- The gallery works on both mobile and desktop.

### 9. Understanding who Lydia is and why to choose her
As a prospective client,  
I want to learn a bit about Lydia and her approach,  
so that I feel more confident choosing her rather than another stylist.

**Acceptance criteria**
- There is an About section that introduces Lydia in a friendly, professional way.
- It explains what makes her services different or special.

### 10. Mobile-friendly experience
As a prospective client using my phone,  
I want the whole site to work well on a small screen,  
so that I can browse services, look at work, and send an enquiry without pinching and zooming.

**Acceptance criteria**
- All main content and navigation are usable on a mobile-sized screen.
- Buttons and links are large enough to tap easily.
- Text remains readable without horizontal scrolling.