Mac OSX identify USB Serial Connection by /dev/tty.usbserial-*.

From that example sudo ./path-to-a3700-utils/wtptp/linux/WtpDownload_linux -P UART -C 1410 -R 115200 -B /path/to/TIM_ATF.bin -I /path/to/wtmi_h.bin -I /path/to/boot-image_h.bin -E
from flag -C replace the * with the proper serial ID. In my case /dev/tty.usbserial-1410 become 1410 in the above command.
