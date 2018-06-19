# class-and-modules-assignment
#q1
class circle:
 def_init_(self,r):
 self.radius=r
 print("radius:",self.radius)
 def getarea(self):
 area=3.14*self.radius*self.radius
 print("area:",area)
 def getcircumference(self):
 per=2*3.14*self.radius
 print("circumference:%.2f"%per)
 obj=circle(5)
 circle
 obj.getarea()
 obj.getcircumference()
 #q2
 class student:
 def_init_(self,name,roll):
 self.n=name
 self.r=roll
 def display(self):
 print("name:",self.n)
 print("roll_number:",self.r)
 s1=student("x",01)
 class student
 s1.display()
 s2=student("y",02)
 class student
 s2.display()
 #q3
 class temperature:
 def_init_(self,temp):
 self.t=temp
 def convertFahrenheit(self):
 fah=(9/5)*self.t+32
 print("Fahrenheit equivalent:",fah)
 def convertCelsius(self):
 cel=(self.t-32)*(5/9)
 print("celsius equivalent:",cel)
 t1=temperature(53)
 class temperature
 t2=temperature(96.8)
 class temperature
 t1.convertFahrenheit()
 t2.convertCelsius()
 #q4
 class moviedetails:
 def_init_(self,mn,an,yr,r):
 self.movie_name=mn
 self.artist_name=an
 self.release_year=yr
 self.ratings=r
 def display(self):
 print("movie:",self.movie_name)
 print("artist_name:",self.artist_name)
 print("release_year:",self.release_year)
 print(ratings_(out of 10):",self.ratings)
 def update(self,new_moviename,new_artistname,new_release,new_ratings):
 print("updating movie details....")
 self.movie_name=new_moviename
 self.artist_name=new_artistname
 self.release_year=new_release
 self.ratings=new_ratings
 movie1=moviedetails("xyz","abc",2000,5.5,)
 moviedetails
 movie2=moviedetials("jkl","iop",2001,7.3)
 moviedetails
 movie1.display()
 movie2.display()
 movie2.update("jkl","ytu",2001,7.5)
 movie2.display()
 #q5
 class expenditure:
 def_init_(self,expenditure,savings):
 self.e=expenditure
 self.s=savings
 def display(self):
 print("expenditure:",self.e)
 print("savings:",self.s)
 def calculate_salary(self):
 self.salary=self.s-self.e
 def display_salary(self):
 print("salary:",self.salary)
 e=expenditure(2240,4000)
 e.display()
 e.calculate_salary()
 e.display_salary()
