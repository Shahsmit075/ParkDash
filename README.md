# ParkDash
Implementing intelligent and real-time governance for Indian street parking in response to surging vehicle numbers and inadequate infrastructure. Addressing traffic congestion and mismatched parking needs.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
    <a href="#tech-stack-used">Tech Stack used</a>
    </li>
    <li>
      <a href="#youtube-link">Youtube Link</a>
    </li>
    <li><a href="#idea/approach-details">Idea/Approach Details</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#show-stoppers">Show Stoppers</a></li>
    <li><a href="#future-aspects">Future Aspects</a></li>
    <li><a href="#contact">Contributors</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
**Smart Parking Systems by Enhancing Space Management :**<br> Our solution aims to create a comprehensive Smart Parking Management System, incorporating features such as real-time availability updates, allowing users to extend their parking time, and advanced booking options. This system streamlines the parking experience, making it convenient for both residents and visitors.



### Tech Stack used : 
![techstacks](https://github.com/Shahsmit075/ParkDash/assets/119691937/4b5f3105-2f52-47cf-aa2f-06e8c4892256)
<!-- GETTING STARTED -->

### Youtube Link :  

## Understanding the Architecture : 
![2sih_22 (5) jpeg](https://github.com/Shahsmit075/ParkDash/assets/119691937/ef8e8f6b-8182-459d-b99d-3d14e7480926)

Introducing the Future of Parking: Your Ultimate Automated Parking Portal

Are you tired of endlessly circling the block in search of parking or dealing with parking hassles? Look no further! Our cutting-edge Automated Parking Portal revolutionizes the way you find, book, and manage parking spaces, offering unparalleled convenience and security for both clients and sellers/renters.

*Client-Friendly Mobile and Web Interface:*
- Seamlessly switch between our mobile and web interfaces, designed to cater to your unique needs.
- Hassle-free registration by uploading your personal details, ensuring a smooth user experience.

*Effortless Parking Booking:*
- Instantly locate available parking spaces nearby by entering your location or simply turning on GPS.
- Browse through parking options, complete with prices and real-time availability.
- Choose between instant booking or pre-booking to secure your spot.
- Set your parking duration, and you're all set! Your parking space is reserved.

*Top-Notch Security with Blockchain:*
- Rest easy knowing that your personal data is stored on a protected blockchain server, ensuring the utmost security and privacy.

*Simple Seller/Owner Listing:*
- Sellers and property owners can easily list their parking spaces by providing essential details.
- Our verification process ensures the quality of listed spaces, and owners can start renting them out.

*Safety Standards and Surveillance:*
- Serious about security? All major parking space owners are required to maintain security standards, including CCTV cameras, for peace of mind.

*Automated Parking System:*
- Our automated system takes parking to the next level. Upon entering, AI-powered cameras automatically detect your vehicle's number plate.
- A unique code is generated and sent to both the client and seller devices.
- The client simply scans the code, and voila! The parking timer starts.
- All CCTV footage and daily data are securely stored on local servers and local storage, with only critical data passing through our main server to our primary storage.
- Integrated Iot Parking Gateway during Entry and Exit , automated with the help of QR (quick-response) code.

*State-of-the-Art Communication and Security:*
- We ensure secure communication between web/mobile interfaces using RESTful APIs.
- Robust JWT(Json WEb Tokens) authentication guarantees the confidentiality of your data.
- Online payments are made easy and secure with Stripe, the industry leader in payment gateways.

*Reliable Hosting and Databases:*
- Our infrastructure is hosted on AWS cloud, ensuring the highest reliability and performance.
- MongoDB powers our primary storage database, while MySQL handles local storage.

This is the future of parking – a smart, secure, and convenient solution designed to simplify your life. Say goodbye to parking woes and embrace the next-generation Automated Parking Portal. Join us today and experience parking like never before!

## Idea/Approach Details :
**(1) Providing Optimal Pricings :**<br> By using Deep Q-Networks (DQN) or Proximal Policy Optimization (PPO) algorithms to adaptively optimize pricing strategies by engaging with the parking environment, responding to rewards tied to revenue and occupancy rates, all in real-time.<br>

**(2) Admin-User Authentication System :**<br>
Introducing an Admin-User Review System to ensure accountability from both sides. Users can provide feedback on admin-listed parking spaces also allowing the administrators to monitor user activity, resolve disputes, and maintain a fair and transparent parking ecosystem. Hence, enhancing the overall experience by helping others find convenient parking spots.<br>

**(3) Privacy :**<br> To enhance user privacy, integrate privacy-preserving algorithms, blockchain for secure record-keeping, identity management, zero-knowledge proofs, and tokenization. Use multi-factor authentication, and secure communications. Implement consent management platforms, and end-to-end encryption, and conduct regular. These tools and practices will safeguard user data and foster trust in our Application.<br>

**(4) ALPR (Automatic License Plate Recognition) Technology :**<br>Integrating ALPR technology with CCTV cameras enhances our parking management system's efficiency and security. These strategically placed cameras capture license plate images, while our ALPR software processes them in real-time, swiftly recognizing license plate data. To further elevate the user experience, we've introduced a QR code feature for quick payments. Upon exit, a unique QR code is generated, allowing users to make instant payments with a smartphone scan. This innovation simplifies the payment process and exemplifies our commitment to efficiency and user convenience.<br>

<!-- USAGE EXAMPLES -->
## Features🌟
**(1) Advance Booking & Time Extension:** Users can plan ahead by reserving parking spots, reducing the hassle of finding parking. Our system also allows easy time extension, ensuring flexibility and a stress-free parking experience.<br>

**(2) Geolocation with Google API:** Our system leverages the Google Geolocation API to provide accurate location services. Users can effortlessly pinpoint available parking spots, optimizing their search and reducing unnecessary congestion. This feature streamlines parking, making it both efficient and user-friendly<br>

**(3) Parking Tier Diversification & Emergency Parking:** ur system categorizes parking spots into tiers (Tier 1, Tier 2, and Tier 3) based on factors such as the availability of security guards, CCTV surveillance, and other amenities, offering varying pricing options following DQN algorithm. Also, we provide dedicated emergency parking spaces, greatly enhancing safety and providing users with invaluable flexibility.<br>

**(4) EV Parking Support:** Observing the increasing popularity of EVs ,we are providing special support for electric vehicles (EVs) with reduced pricing and reservation options, making parking convenient and cost-effective for EV users.<br>

## Show Stoppers
 **[1] Image Reporting and Community Accountability:** Our system allows users to report illegal parking by uploading images. To maintain accountability, we introduce a "Community Tab" where users can vote (like/dislike) on reported images. This collective voting system increases or decreases a user's rating based on the accuracy of their reports, fostering responsible reporting and community participation in upholding parking standards.<br>

 **[2] Geolocation with Google API:** Our system leverages the Google Geolocation API to provide accurate location services. Users can effortlessly pinpoint available parking spots, optimizing their search and reducing unnecessary congestion. This feature streamlines parking, making it both efficient and user-friendly<br>
 
 **[3] Sensor Technology and QR Code Payment Integration:** We employ sensor technology at entry and exit points to streamline parking. As vehicles enter and exit, sensors detect their presence, automatically recording entries and exits. Also, we’ve integrated QR code support for swift payments. Users receive a QR code upon exit, which they can easily scan with their smartphones for instant payment processing.<br>

## Future Aspects 
**[1]** EV charging infrastructure integrated into parking facilities to support the growing trend of electric vehicles.<br>
**[2]** Integration with IoT (Internet of Things) technology to create a network of connected sensors and devices that can monitor and manage parking spaces in real-time.<br>
**[3]** Enhanced security measures, including surveillance and emergency response systems.<br>



<!-- CONTACT -->
## Contributors

- [@Shahsmit075](https://github.com/Shahsmit075) - shahsmit075@gmail.com <br>
- [@Sudhanshu-Bharti](https://github.com/Sudhanshu-Bharti) - shhubham01legend@gmail.com <br>
- [@Om136](https://github.com/Om136) - omvpatel173@gmail.com <br>
- [@ishanRaj03](https://github.com/IshanRaj03) - ishanraj1908@gmail.com <br>
- [@sohamhaldar](https://github.com/sohamhaldar) - sohamhaldar25@gmail.com <br>
- [@Neetu03](https://github.com/Neetu03) - neetuchoudhary03022004@gmail.com <br>

Project Status : Ongoing <br>
