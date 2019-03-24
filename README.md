<h1> Veterinary Clinic of Tourrettes </h1>

My project gives visibility to a prospective Veterinary Clinic for my sister who is a Doctor in Veterinary Medecine. <br>

It provides information on the services provided by this "hypothetical" clinic, the location, information about the studies and experiences about the Doctor and functionalities to contact the clinic either by a contact form (that can be used by pharmaceutical companies for instance), a request form (for clients wanting to book an appointment) or directly by phone and/or emails.<br>

The website has both English and French versions as there are a lot of English people established in the South of France and tourists during the summer time. <br>

This website was developed as a prototype that could be directly used the day my sister launches her Veterinary Practice, which is a goal that she has in the medium term. That is why it already has all the features of an existing clinic.

<h2>UX</h2>
The purpose of this website is to provide visibility to the clinic in an area where the location is key. <br><br>
The layout of the website is very simple but classy, the content is purposely kept very minimalist (so that the user is not drawn into a myriad of paragraphs…) but with effective information: how to reach out to us, where to find us and who are we. 
Even though the vast majority of end users are prospective pets’ owners looking for a practitioner in his/her geographical area, the challenge was to have a website that could also be useful for other users such as: persons in need of emergency services for their pets, pharmaceutical companies, practitioners looking for a collaboration, associations… <br><br>
Also the specificity of this clinic is that it provides Emergency Services. That is the reason why the content needed to be focused on “how to reach out to us” – through phone still remains the most effective way to reach out to the clinic in case of Emergency – and where the clinic is located (Embedded Google Maps). <br><br>
For users that are not in a distressed situation, the website should also address their needs, that is why all the services provided are presented, as well as the information about the education and the experience of the Doctor are provided (practitioner looking for a collaboration for instance). For users who are looking for a practitioner to follow-up their animals on a regular basis, they also have the possibility to book appointment online and/or contact the clinic using the contact form at the end. 

<h2>Features</h2>

<h3>Existing Features</h3>
<ul>
<li>Modal Form using Bootsrap allows users to request an appointment</li>
<li>Embedded Google Maps allows users to easily locate the clinic without being redirected to an external google maps link.</li>
<li>The contact form enables professional users (other practitioners, or pharma companies) that want to interact with the clinic to directly contact them.</li>
<li>The footer enables to directly trigger a call, open an email to contact the clinic.</li> 
</ul>

<h3>Features Left to Implement</h3>
<ul>
<li>Improve the interactive functionalities such as booking an appointment through the modal form by selecting available time slots with a calendar.</li>
<li>Add other sections such as a Blog section on Veterinary Medecine, or any papers published by the doctor.</li>
<li>Add new functionalities to increase interaction with the user: adding an intranet space for existing customer.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li>HTML</li>
<li>CSS</li>
<li>Boostrap (3.3.7)</li> <ul>
  <li>	to implement a Carousel on the home page </li>
  <li>to generate a modal form to request an appointment </li>
  </ul>
  </li>
</ul>

<h2>Testing</h2>

<p>
This site was thouroughly tested manually, please find below the details of the testing. The main user story for this website would be the following: a prospective customer would like to have information on the services provided by the clinic, be able to locate the clinic and contact them easily.
</p>

<p>

<br>The navigation bar enables to click any section of this single page website. The navigation bar style succesfully changes according to the section the user hits while scrolling. The user can also click on the section to be redirected to the corresponding section. There is also the possibility to change the language to French (or English). 
When clicking on the logo at the top left side of the navigation bar the user is redirected succesfully to the index page. This navigation bar changes to a collapsable bar with a hamburger button on smaller devices to ensure better responsiveness, this was done using bootstrap. 

<br> The section "services" gives information about all the services provided at the clinic, then, the "doctor" section provides information about the vet, a picture with a short description as well as a detailed timeline of her cursus.
In the "About Us" section, all the information regarding the emergency services and consultations are provided. It is possible to call or send an email by clicking on the anchor, it will automatically trigger the default application to call or send an email directly from the device.
It is also possible to check the address by clicking on the "Check Maps", this link redirects the user to a google maps snippet so that the user can locate the clinic. It is then possible to get back by clicking on the button "back" below the map which prevents the user from having to use the browser arrow (which would be a poor user experience).
The user has the possibility to request an appointment online, by clicking this button, a module form pops and the user is invited to enter his/her personal information so that the clinic can get in touch. The purpose is to improve that functionality later on so that it is more interactive and the user can directly book an appointment online according to the availabilities. 
It is also possible to contact the clinic for more general purposes (partnership, business purposes etc...) through a contact form in the "Contact Us" section. 
The contact form as well as the module form are set up so that the form cannot be submitted (error message) if:
 <ul>
  <li> the email is not in the correct format </li>
  <li> the phone does not contain only number</li>
</ul>

<br>The footer is a reminder of key information to contact and get information on the clinic. As it was done in the "About Us" section, by clicking the email and phone anchor, it will automatically trigger an email or a call from the device.  
By clicking the two glyphicons of twitter and facebook, a new tab (by using the attribute 'target="_blank"') opens which redirects the user to the corresponding social media page. Please note that it is purposely redirecting to the main page of the social media as there are no pages created for the clinic yet (since this is a hypotehtical clinic at the moment). 

</p>

<p>
Compatibility & Responsiveness 

This site was tested across the following browsers to ensure that all functionalities render well in different browsers:
<ul>
  <li> Safari </li>
  <li> Google Chrome</li>
  <li> Mozilla Firefox </li>
  <li> Internet Explorer </li>
  <li> Opera </li>
</ul>

I also was able to test the responsiveness of the webiste by testing it directly on my Phone (Huawei P9 Lite) and thanks to Chrome Developer tool, I tested my website on the following devices:
<li> Galaxy S5 </li>
  <li> Pixel 2 </li>
  <li> Pixel 2 XL </li>
  <li> iPhone 5/SE </li>
  <li> iPhone 6/7/8 </li>
  <li> iPhone 6/7/8 Plus </li>
  <li> iPhone X </li>
  <li> iPad </li>
  <li> iPad Pro </li>

Following this testing, I realised that the "About Us" section was not rendering well. 
Indeed at first, I added "overflow: auto" but this was a poor user experience for devices when scrolling this section. 
So I added media-queries to resize the info boxes of this section so that they would all fit in the (picture) background. 

</p>

<h2>Deployment</h2>
This site is hosted using GitHub and directly deployed using the master branch with a unique contributor being myself. <br><br>
You can access to my deployed website through the following <a target="_blank" href="https://alexiadelorme.github.io/project-clinic/index.html">link</a>. <br><br>
You can also access to my source code directly through the repository I have created through the following <a target="_blank" href="https://github.com/AlexiaDelorme/project-clinic"> link</a>.

<h2>Credits</h2>

<h3>Content</h3>
The content was entirely written by myself and reviewed by my sister regarding the accuracy of information provided in the “About our Doctor” section. 

<h3>Media</h3>
<ul>
  <li>All the photos used in the “home”, “services” and “contact” sections are from this free pictures library : <a target="_blank" href="https://unsplash.com/"> https://unsplash.com/</a>. </li>
  <li>The pictures used in the “doctor” and “about us” (background with the mountains) are personal pictures taken by myself.</li>
  <li>All the glyph-icons I used were taken on Font Awesome: <a target="_blank" href="https://fontawesome.com/v4.7.0/icons/"> https://fontawesome.com/v4.7.0/icons/</a></li>
  <li>For my font style I used the Google Font library: <a target="_blank" href="https://fonts.google.com/"> https://fonts.google.com/</a></li>
</ul>

<h3>Acknowledgements</h3>
<ul>
  <li>In terms of general structure of my project I received inspiration mostly from the Sample Project (Grade 5) – Portfolio of Hayley Schaffer. </li>
  <li> Regarding the background positioning, I used the recommendations provided in this link: <a target="_blank" href="https://css-tricks.com/perfect-full-page-background-image/">https://css-tricks.com/perfect-full-page-background-image/</a>. </li>
  <li>The implementation of my carousel was done thanks to the tutorial provided by W3 Schools: <a target="_blank" href="https://www.w3schools.com/bootstrap/bootstrap_carousel.asp">https://www.w3schools.com/bootstrap/bootstrap_carousel.asp</a>. </li>
  <li> In terms of general layout I received inspiration mostly from the website of <li> <a target="_blank" href="https://www.veterinaire-alliance.fr/ ">this clinic</a></li> located in France as well as this webiste (especially the use of the classy blue font-color) : <a target="_blank" href="http://athospartners.com">http://athospartners.com</a>.</li>
  <li>In terms of benchmark I also researched websites of clinics located in France (and specialized in Emergency Services). I was therefore able to structure my content after studying the following websites:
    <ul>
    <li> <a target="_blank" href="https://www.fregis.com">https://www.fregis.com</a></li>
   <li> <a target="_blank" href="http://www.urgences-veterinaires-delta-06.fr/ ">http://www.urgences-veterinaires-delta-06.fr/</a></li>
    </ul>
  </li>
  <li>For the “Doctor” section, I built the timeline (without almost any modifications as it rendered pretty well on my section) by using the code implemented during the Mini Project (building a CV website) at the end of the User Centric module. </li>
  <li>To embed the google maps in the “about us” section I used the code generated in the Embed Google Maps generator: https://embedgooglemaps.com/en/. I added minor modifications in terms of position so that it rendered better on my website. </li>
</ul>

