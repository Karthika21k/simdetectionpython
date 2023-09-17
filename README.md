# simdetectionpython
import phonenumbers
from task import num
from phonenumbers import geocoder

ch_num = phonenumbers.parse(num,"CH")
print(geocoder.description_for_number(ch_num,"en"))

from phonenumbers import carrier
service_num =phonenumbers.parse(num,"RO")
print(carrier.name_for_number(service_num,"en"))
num = "+91 9025"
