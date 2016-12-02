# mfibeta
ubnt mFI beta instalation for Docker

Try to start with:

docker run -ti -v /var/log/mfi:/mFi/logs -v /var/lib/mfi:/mFi/data --restart=always --net=host dynodix/mfibeta

