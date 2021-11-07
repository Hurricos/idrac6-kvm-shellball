# idrac6-kvm-shellball

The script in this repository allows you to connect to the networked KVM of an iDRAC6 enterprise card found on e.g. the Dell R510.

The script unpacks `avctKVM.jar` and then passes on its command-line options to java.

You may run this script as, e.g.:
    
 ./idrac6_connect.sh -U admin -P calvin -h 192.168.0.4

## Inspiration

The basic idea for this tool is taken from [this gist](https://gist.github.com/xbb/4fd651c2493ad9284dbcb827dc8886d6).
