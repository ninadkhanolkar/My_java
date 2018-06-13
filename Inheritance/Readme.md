Method overloading
Access specifier should not reduce visibility

instanceOf operator :eg.  	
public void manageLT(LivingThing livingThing) {
		livingThing.eat();
		livingThing.sleep();
		if (livingThing instanceof Human) {
			Human human = (Human) livingThing; //explicit casting. 
			human.study();
		}
		livingThing.work();
    
    
	
                           
