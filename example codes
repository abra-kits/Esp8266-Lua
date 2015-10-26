print("Blink Example")
gpio.mode(1, gpio.OUTPUT)

local led=1;
tmr.alarm(2,1000,1,function()
	if led == 1 then
		gpio.write(1, gpio.HIGH)
		led=0;
	else 
		gpio.write(1, gpio.LOW)
		led=1;
	end
end)
