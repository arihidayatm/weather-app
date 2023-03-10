# weather-app

# index.html

Kode tersebut adalah sebuah HTML document yang berisi elemen-elemen HTML, CSS, dan JavaScript.
Berikut adalah prosedur untuk menjalankan code tersebut:

<ul>
<li>Buka teks editor, seperti Notepad atau Sublime Text.</li>
<li>Salin code di atas dan paste-kan ke dalam teks editor.</li>
<li>Simpan file dengan nama "index.html" pada folder yang diinginkan.</li>
<li>Buka file "index.html" dengan web browser seperti Google Chrome atau Mozilla Firefox.</li>
Halaman web "Weather App" akan ditampilkan di web browser. Anda dapat mencari cuaca kota yang diinginkan dengan memasukkan nama kota pada kolom pencarian.</li>
<li>Anda dapat menyesuaikan pengaturan aplikasi dengan mengklik ikon roda gigi di bagian kanan atas layar. Di sana, Anda dapat memilih mode, skala suhu, tema, dan menutup pengaturan.</li>
</ul>
Kode tersebut menggunakan beberapa library eksternal, yaitu Font Awesome untuk ikon, Google Fonts untuk jenis huruf, dan Lipis Flag Icons untuk menampilkan bendera negara. Kode JavaScript pada file "main.js" digunakan untuk mengambil data cuaca dari API OpenWeatherMap.

# style.css

The code is a CSS code used to style a web page. It defines styles for various elements of the page, such as the font, background, header, and search bar.

The code begins by importing a font from Google Fonts and setting default styles for all elements on the page, such as setting the margin and padding to zero, and setting the box-sizing property to border-box. It also sets the font-family to 'Poppins', sans-serif.

The container class sets the width and height to 100vw and 100vh, respectively, and applies a linear gradient and an image background to it. The header class sets the style for the header of the page, including its height, position, background, and font size. It also sets the backdrop-filter property to blur the background and adds a text shadow.

The set_c class sets the style for a button used in the header, including its font size and position. The header h2 class styles the heading of the header, including the text shadow, flex property, and margin.

The w_cont class sets the style for the main content area of the page, including its width, height, background, border radius, and padding. It also sets the box shadow, border, and backdrop-filter properties, and adds an animation and a transition effect.

The search_div class sets the style for the search bar, including its width, height, padding, border radius, and margin. It also sets the display, align-items, and justify-content properties to center the search bar. The search bar itself is an input field with a placeholder text and a search icon styled using the fa-search class.

The weather_in class sets the style for the heading of the weather information section, including its font size, color, and font weight. The temp class styles the temperature display, including its font size, weight, and color. The icon class styles the weather icon, including its size, position, and background image. The conditions class sets the style for the weather conditions section, including its display, width, height, padding, and border radius.

# main.js

The code is a JavaScript program for a weather app. It fetches the user's location data and displays the weather information of that location using the WeatherAPI.com API. The program uses XMLHttpRequest to make requests to the API and jQuery for DOM manipulation.

The program starts by making a request to the 'https://ipapi.co/json/' API to get the user's location data. The location data is used to construct the URL for the weather data request to the WeatherAPI.com API. The request is made with XMLHttpRequest and the response is parsed as JSON.

The program then updates the DOM with the weather data obtained from the API. The weather data includes the temperature, humidity, wind speed, timezone, and weather condition. The program also updates the background image of the page based on the user's selection and changes the theme of the page based on the user's selection.

The program uses jQuery to add event listeners to the page elements. The 'focus' event is added to the input element to clear its value when the user clicks on it. The 'click' event is added to the 'settings' and 'close' buttons to show and hide the settings container respectively. The 'click' event is added to the theme buttons to change the background and theme of the page.

The program also adds a 'change' event listener to the temperature unit radio buttons to toggle between Celsius and Fahrenheit units.

Copyright @MAH Dev
