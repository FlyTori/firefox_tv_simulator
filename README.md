#### **Install simulator** (for Mac)

1. Open terminal

2. Install homebrew (visit this site for latest install info: http://brew.sh/)
> ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

3. Use homebrew to install git
> brew install git

4. Use home-brew to install node
> brew install node

5. Install gaia-develop (thanks to developer Yifan for this [package](https://www.npmjs.com/package/gaia-develop))
> npm install -g gaia-develop

6. git clone gaia (you can change the directory)
> git clone https://github.com/mozilla-b2g/gaia

7. Download and install Firefox Nightly, named b2g-xxxxxxxxxx-US.mac64.dmg, at: 
> http://ftp.mozilla.org/pub/mozilla.org/b2g/nightly/latest-mozilla-central


#### **Open simulator**

1. Open gaia folder (if you changed the directory in step 5, open corresponding directory)
> cd ~/gaia

2. Pull latest code & open simulator
> git pull origin master; gaia-develop tv

#### **Function keys**
* Back (TV) = ESC (laptop)
* Home (TV) =  (1) home button at bottom, or (2) "fn" + "←"
* Option (TV) =  (1) right click on mouse, or (2) "double click" on touch-pad
