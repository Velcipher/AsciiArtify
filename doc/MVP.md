# MVP
## Access To The Application
```sh
kubectl port-forward -n demo svc/ambassador 8000:80&
```
## Just find the test image in .png format
```sh
wget -O test/appple.png https://pngfre.com/wp-content/uploads/apple-95-270x300.png

```
## Convert image
```sh
curl -F 'image=@test/apple.png' localhost:8000/img/
```
# App work demonstration
https://files.fm/f/bbhamnct7h

# ArgoCd setting up demo
https://files.fm/u/d4nz9sabmr

# А ще я подумала, що треба свою програму простеньку писати, тож скину і її (зате навчилася маніфести писати 😅 )

https://files.fm/u/8smrrr3rpz
https://files.fm/u/uzw2zx4k26

