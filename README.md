polipo docker image build on alpine linux.

docker run -it --rm hitian/polipo polipo -h

show config example:

docker run -it --rm hitian/polipo cat /etc/polipo/config


for arm32 raspberry pi or tinker board

use image hitian/polipo-arm32
