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
![Image](./demo_go_work_demonstration.mp4)

# ArgoCd setting up demo
![image](./demo_go_ArgoCD_demonstration.mp4)

# А ще я подумала, що треба свою програму простеньку писати, тож скину і її (зате навчилася маніфести писати 😅 )

![image](./test_work_demo.mp4)
![image](./test_ArgoCD_demo.mp4)