# <img src="https://user-images.githubusercontent.com/70295997/217133678-615791c3-1a0b-4cee-94a8-fd345ec767e8.png" width=40> Mobile devices have been evolving, along with the respective cellular networks, bandwidths and protocols. 

<img src="https://user-images.githubusercontent.com/70295997/217134148-1dad5503-10c4-421f-b66c-79243f8fc6fd.png" width=40> 1G standard was first used in 1981. And in 2018, [***5G***](https://en.wikipedia.org/wiki/5G) was introduced, whose signal quality can handle dense cells on millimeter waves.
Below captioned are the list of mobile phone standards and the comparison chart among them.

* [List of mobile phone generations](https://en.wikipedia.org/wiki/List_of_mobile_phone_generations)

* [Comparison of mobile phone standards](https://en.wikipedia.org/wiki/Comparison_of_mobile_phone_standards#:~:text=called%20cell%20breathing.-,Comparison%20table,-%5Bedit%5D)

<img width="1000" src="https://user-images.githubusercontent.com/70295997/217127870-cbac3f28-addb-46cb-a928-204eeea4f441.png">

<img width="1000" src="https://user-images.githubusercontent.com/70295997/217128078-8a56aae7-9755-4f47-b446-5797c7c4413f.png">

<img width="1000" src="https://user-images.githubusercontent.com/70295997/217128393-df589e9d-e031-40e5-9d1f-9306bd42410b.png">

<img width="1000" src="https://user-images.githubusercontent.com/70295997/217128647-9dff06fd-b87e-4641-ab4a-88453b239828.png">


<img src="https://user-images.githubusercontent.com/70295997/217134386-06e74064-8e5f-4070-aaf4-2fe62081ca55.png" width=40> 5G is a cutting-edge network protocol designed to provide faster and smoother data transfer. It boasts high speed and has the capability to handle a larger number of connections with greater accuracy and lower latency than 4G networks. As technology evolves, more devices and mobile apps are requiring faster internet connectivity. 5G will meet these demands and enable innovative uses such as smart home appliances, UHD streaming, virtual reality, and connected-city safety. For SDETs and DevOps, the transition to 5G involves extensive [mobile app testing](https://github.com/lana-20/i_sliced_up_fun-SQA-mnemonic#readme) to ensure compatibility with previous protocols, secure against security vulnerabilities, and optimize apps to fully utilize the capabilities of this ultrafast network.

5G is not simply an improvement on 4G network but a completely new communication protocol. It requires new devices, radio stations, and careful planning for its implementation. While some major cities in the US already have 5G, it is still being fine-tuned for wider commercial and consumer use.

📝 Two things to note about 5G: ① it is not your 5GHz Wi-Fi at home, which is a short-range Wi-Fi band, and ② it is not "millimeter-wave 5G", a marketing term used by some mobile carriers for 5G-certified devices that still use 4G towers and have similar bandwidth and limitations as 4G.

<img src="https://user-images.githubusercontent.com/70295997/217134752-25835c45-a1d3-4365-b837-a7cf4fb2a611.png" width=40> The main difference between 5G and 4G is speed. 5G can handle higher volumes of complex data at speeds up to 20 times faster than 4G, thanks to its use of radio frequencies between 30 GHz and 300 GHz, which provide wider channels and less interference.

5G also enhances the user experience by supporting more device connections, faster transfer of large data, and improved video quality for AR/VR and video streaming.

For SDETs and DevOps, the ***challenges*** of 5G include compatibility with older devices and protocols, interoperability across apps, platforms, and operating systems, and security. The adoption of 5G will also require upgrading existing 4G towers and app architecture.

5G presents ***opportunities*** for app developers to create new UIs with richer functionality, but DevOps will need to use AI/ML algorithms for continuous improvement. 5G is also a key enabler for IoT, as it can support a large number of devices with longer battery life and real-time communication.

<img src="https://user-images.githubusercontent.com/70295997/217135623-bfefdf8b-4cd1-4ecf-8d1a-c6a9722e4907.png" width=40> As an SDET, when I think about transitioning or testing my app and addressing any digital challenges I have in the 5G, there are some key points which I consider on a high level for a  <img src="https://user-images.githubusercontent.com/70295997/217136208-9ae925b3-9e60-4285-946c-40745b4519ea.png" width=40>  ***Test Plan***.

<img width="600" src="https://user-images.githubusercontent.com/70295997/217128913-3d7b014d-4112-4364-9886-23809d841cc1.png">

1. **It's app dependent**: If I am in a specific vertical, I have my own considerations. But the generic testing considerations, on top of the app dependant functionality, are captured in the following points.
2. **Compatibility (5G, 4G, Older)**: Make sure my app is compatible with 5G, 4G or older network generations. It's important because not the entire world is 5G ready. There are different areas, even in the U.S. as well as different countries in the world, that haven't adopted 5G to a full scale. This means I have a lot of users still running on the older network configurations. I want to make sure that the app operates well acroos all these networks. 
If I have a specific feature that is 5G related, I want to make sure that is not causing any poor user experience when running on 4G or when moving from 5G to 4G or to WiFi.
3. **Interoperability (App Architecture)**: I must be aware of the architecture to know what needs to happen with the app to make it fully ready to work across all the different 5G use cases, locations, and devices.
4. **Security (Multi-Channels)**: 5G already enables apps to communicate across different channels, cities, IoT, NFC devices, cars, etc. This means that my app, which stores a lot of sensitive data, actually transmits this data across multiple channels towards multiple physical devices that I don't really control. I want to make sure that I have a good security layer and monitor the app behavior in order to avoid anything in danger.
5. **Coverage and Locations**: Not all the geographies fully support 5G. And in different geogrpahies, I see different smartphones and tablets, some of which support 5G and some don't. I want to have a good geo map coverage mapping that allows me to fully release the app confidently, knowing that it runs in 5G, 4G across different geographies where my users use the app. This gives me the peace of mind heading towards the future.

Wrap-Up: 5G is here, it's well adopted. A lot of app devs and testers today already look into multiple use cases, verifying that the existing app can reach the users and delight them with the high user experience. As an SDET, I want to ascertain that my app is ready for 5G, as well as ensure that it's well tested with high quality goals.


