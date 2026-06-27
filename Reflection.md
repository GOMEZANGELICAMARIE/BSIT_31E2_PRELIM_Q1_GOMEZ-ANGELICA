Why did you use inheritance?
I use inheritance because it has the same base class and all transports are vehicles. They also share the same type and each vehicles has unique behavior in terms of using common features

Why did you use interfaces?
I use interfaces because it represents the each capabilities and behaviors of vehicles that consists of driving, flying, and sailing and different classes can implement the behaviors that can be supported.

Can Helicopter inherit from both Vehicle and Airplane? Why or why not?
No, because C# doesn't support double or multiple inheritance and it only supports single inheritance because each class can inherit from one base class only and a single vehicle like helicopter can inherit vehicle only.

Why can Helicopter implement both IFlyable and IDriveable?
Because C# can support a class to have multiple interfaces because interfaces is about what a vehicle can do and helicopter can fly and drive at the same time.

If a Submarine can both sail and dive, how would you design it?
I should create a Submarine file or class that will inherit from the vehicle and be a sailable and diveable in interface.