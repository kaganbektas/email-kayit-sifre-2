# import os
# username="***"
# password="***"
# com="wget -q -O - https://"+username+":"+password+"@mail.google.com/mail/feed/atom --no-check-certificate"

# temp=os.popen(com)
# msg=temp.read()
# index=msg.find("<fullcount>")
# index2=msg.find("</fullcount>")
# fc=int(msg[index+11:index2])

# fc = msg[index+11:index2]

# if len(fc) < 1 :
#     print ("Hicbir bilgi alinamadi..")
# elif fc == "0":
#    print ("0 new")
# else:
#    print ("%s  new") % (fc)
