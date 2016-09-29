# Robotic-1

void hard_fly(); //define motors that makes motors fast forward

void turn_right(); //define function that turn left
int main() //define main funcion
{
    hard_fly(); //execute hard fly function
    turn_right(); //execute turn right
    hard_fly(); //execute hard fly

return 0; //returns integer 0
} //end main function
void hard_fly() //define hard fly
{
    mator(1,100);
	mator(2,100);
	msleep(5000);
}
void turn_right()
{
    motor(1,70);
    msleep(4000);
}
