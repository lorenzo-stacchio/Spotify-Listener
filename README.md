<p align="center">
<img alt="ViewCount" src="https://views.whatilearened.today/views/github/MShawon/YouTube-Viewer.svg">
</p>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=06B121&lines=Hi%2C+Spotify+Listener!)](https://git.io/typing-svg)


# Spotify Listener
Simple program to increase Spotify listen written in Python.

**Disclaimer:** This has been developed for educational purposes only. Any action you take using this script is strictly at your own risk. I will not be liable for any losses or damages you face using this script.

**Cons:** There will be some view drop always. 

# Topics
[Requirements](https://github.com/MShawon/YouTube-Viewer#requirements)  
[New Update](https://github.com/MShawon/YouTube-Viewer#new-update)  
[Features](https://github.com/MShawon/YouTube-Viewer#features)   
[Proxies](https://github.com/MShawon/YouTube-Viewer#proxies)    
&ensp;&emsp;[Free Proxy](https://github.com/MShawon/YouTube-Viewer#free-proxy)  
&ensp;&emsp;[Premium Proxy](https://github.com/MShawon/YouTube-Viewer#premium-proxy)  
&ensp;&emsp;[Rotating Proxy](https://github.com/MShawon/YouTube-Viewer#rotating-proxy)  
[HTTP API](https://github.com/MShawon/YouTube-Viewer#http-api)  
[Config.json](https://github.com/MShawon/YouTube-Viewer#configjson)  
[Urls](https://github.com/MShawon/YouTube-Viewer#urls)    
[Search](https://github.com/MShawon/YouTube-Viewer#search)    
[Live Stream](https://github.com/MShawon/YouTube-Viewer#live-stream)    
[YouTube Music](https://github.com/MShawon/YouTube-Viewer#youtube-music)    
[Fast VPS](https://github.com/MShawon/YouTube-Viewer#fast-vps-with-unlimited-traffic)         
[Windows](https://github.com/MShawon/YouTube-Viewer#windows)  
&ensp;&emsp;[Binary Release](https://github.com/MShawon/YouTube-Viewer#binary-release)  
&ensp;&emsp;[Installation](https://github.com/MShawon/YouTube-Viewer#installation)  
&ensp;&emsp;[Usage](https://github.com/MShawon/YouTube-Viewer#usage)  
[Linux / Mac](https://github.com/MShawon/YouTube-Viewer#linux--mac)  
&ensp;&emsp;[Installation](https://github.com/MShawon/YouTube-Viewer#installation-1)  
&ensp;&emsp;[Usage](https://github.com/MShawon/YouTube-Viewer#usage)  
[Best Practices](https://github.com/MShawon/YouTube-Viewer#usage-1)  
[Issues](https://github.com/MShawon/YouTube-Viewer#issues)  
[Credits](https://github.com/MShawon/YouTube-Viewer#credits)  



# Requirements
 * **Python 3.7.x-3.11.x**
 * High speed Internet Connection
 * Good proxy list (http, https, socks4, socks5)
 * Google Chrome installed on your OS (not Chromium)

# Proxies
 *[IPRoyal](https://iproyal.com?r=18862) offers datacenter and residential proxies. The Royal Residential proxies have a large pool with addresses in over 195 countries all over the world, so they can generate a massive number of views. IPRoyal agreed to provide an additional discount of 5% which adds up to current bulk discounts! To get this incredible 5% discount, with bulk discounts for Royal Residential proxies, use the discount code: `youtubers5`*


* ## Free Proxy
   Try not to use free proxies. But if you have a paid subscription and you want to use authenticated IP feature, then you can use the free proxy category. Provide your text file path (where you saved the proxies) when the script asks for a proxy file name or a proxy API.
   N.B: Available for **http(s)/socks4/socks5**
   
* ## Premium Proxy
   Proxies with authentication can also be done. To do so put your proxies in this format `username:password@ipaddress:port`or `ipaddress:port:username:password` in a text file. Every single line will contain a single proxy. Provide your text file path when the script asks for a proxy file name or a proxy API.
   
   N.B: Only available for **http** type proxy.

* ## Rotating Proxy
   You can also use the rotating proxies service. You can either authenticate your IP on your proxy provider service and use `ipaddress:port` as Main Gateway. 
   N.B: Available for **http(s)/socks4/socks5**

   Or direct use username:password combo like this `username:password@ipaddress:port` or `ipaddress:port:username:password` as Main Gateway.

   N.B: Only available for **http** type proxy.
   You can use proxy API too.

# HTTP API
   Live logs fetched every 10 seconds and statistics in graphs are available on http://localhost:5000/ .Or [http://ip_of_your_pc:5000/](http://ip_of_your_pc:5000/) use this to access from another device under same network. A SQLite Database is being used  to store your generated views from this script. 
   Last 200 logs from scripts are fetched every 10 seconds to show on website and graph is updated every 5 minutes.
 
 # Best Practices
  To get the most out of this script you should maintain these things.
  * Don't use HEADLESS mode. Because no IP leak prevention, fingerprint defending, etc. can be done in headless mode.
  * Youtube doesn't count views from the same IP after a certain time. Like, don't expect to get 100 views from 10 proxies. If you want more views, try to use a lot of premium proxies(free proxies are flagged by most websites). DO NOT use TOR proxies.
  * In a nutshell, you need Rotating proxies to get the best result. But the IP MUST NOT change on each request. Set the sticky session or TTL to 5 to 15 minutes.
  * For IPRoyal it would be *Royal Residential Proxies*, not Static Residential proxies
  * Use both [urls.txt](https://github.com/MShawon/YouTube-Viewer#urls) and [search.txt](https://github.com/MShawon/YouTube-Viewer#search)
  * And use as many [urls](https://github.com/MShawon/YouTube-Viewer#urls) and [keyword::::title](https://github.com/MShawon/YouTube-Viewer#search) as you can. Don't use just one video.
