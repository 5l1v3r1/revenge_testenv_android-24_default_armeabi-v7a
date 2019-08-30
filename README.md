Android armeabi-v7 API24 image for testing `revenge`.

Run with:

```bash
sudo docker run -it --rm --network host --privileged -v /tmp/.X11-unix/:/tmp/.X11-unix/ -e DISPLAY=$DISPLAY -v $HOME/.Xauthority:/root/.Xauthority bannsec/revenge_testenv_android-24_default_armeabi-v7
```
