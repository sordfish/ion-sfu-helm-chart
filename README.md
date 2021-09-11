# ion-sfu-helm-chart
Helm Chart for https://hub.docker.com/r/pionwebrtc/ion-sfu/


# Example

docker run -p 7000:7000 -p 50051:50051 -p 5000-5200:5000-5200/udp pionwebrtc/ion-sfu:latest-allrpc -c /configs/sfu.toml -gaddr :50051 -jaddr :7000 -paddr :9876 -maddr :8100

7000
50051
5000-5200?

To be accessed as a service by other pods E.G. ion-sfu-gstreamer-send


--dry-run=client