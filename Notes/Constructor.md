    π  Constructor is a special method which is invoked automatically at the time of object creation. 
    
    πIt is used to initialize the data members of new object generally. 
    
    πThe constructor in C++ has the same name as class or structure

    πAnother constructor can be made ,  it can be parameterized .


    class  Car{
        private: 
            int tyers;
            string carName;

        public: 

            Car(){
                cout <<"Constrcutor called ";
            }
    };

    main(){
        Car Driver1;
    }



 πͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺπͺ

   * Copy Constructor
      π  A Copy constructor is an overloaded constructor used to  declare and initialize an object from another object.
