# 🇺🇦 Ukrainian Flowtron TTS

Trained models based on https://github.com/egorsmkv/flowtron

## Install

```
git clone https://github.com/egorsmkv/flowtron

cd flowtron

# Next, read NOTES.txt
```

## Usage

```
python3 inference.py --eng 0 --sigma 0.5 -c config.json -f model_60000 -w waveglow_256channels_ljs_v3.pt -t "Вітаю вас, мене звати Лада" -i 0
```

## Look more

- Ukrainian RADTTS: https://github.com/egorsmkv/ukrainian-radtts
