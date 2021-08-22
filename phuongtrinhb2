import math

print("GIAI PHUONG TRINH BAC 2 AX^2 + BX + C = 0")
a = int(input("nhap he so a: "))
b = int(input("nhap he so b: "))
c = int(input("nhap he so c: "))

if a == 0:
	if b  == 0:
		if c == 0:
			print("phuong trinh co vo so nghiem")
		else:
			print("phuong trinh vo nghiem")
	else:
		x = round(-c/b,2)
		print("phuong trinh co mot nghiem x = " + str(x))
else:
	delta = b**2 -(4*a*c)
	if delta < 0:
		print("delta < 0 => phuong trinh vo nghiem")
	elif delta == 0:
		x = round(-b/(2*a),2)
		print("delta = 0 => Phuong trinh co nghiem kep x = " + str(x))
	else:
		x_1= round((-b + math.sqrt(delta))/(2*a),2)
		x_2= round((-b - math.sqrt(delta))/(2*a),2)
		print("delta > 0 => phuong trinh co 2 nghiem phan biet:")
		print("X_1 = " + str(x_1))
		print("X_2 = " + str(x_2))
