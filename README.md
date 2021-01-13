# basic
just basic python
class Python:
    def __init__(self, ram, cpu,mom,dad,bro):
        self.ram = ram
        self.cpu = cpu
        self.mom = mom
        self.dad = dad
        self.bro = bro

    def func(self):
        print("computer ram and cpu", self.ram, self.cpu)
    def family(self):
        print("my families name is",self.mom,self.dad,self.bro)


comp1 = Python(input("enter 1"),input("enter 1.2"),"kamlo","mani","ashu")
comp2 = Python(input("enter 2"),input("enter 2.2"),"none","none","none")


comp1.func()
comp1.family()
