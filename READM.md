1. Run browser side https://github.com/freddyli7/webrtc-example-webside with `python3 -m http.server 8080` and open localhost:8080
2. Create the offer from the browser
3. Open the browser console and cpoy the base64 string
4. Save the string into offer.b64 file 
5. Run the rust code with `Cargo run`
6. Copy the answer from rust side the paste it into browser side.