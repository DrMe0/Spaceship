--This is turtle 1.
--Program starts at on back of spaceship.
--rednet.open("right")
--Function for breaking stuff and placing things on the back
local IFPLACEORNOT = "NO"
local function PLACEANDBREAK()
  turtle.dig()
  if IFPLACEORNOT() == YES then
    turtle.forward()
    turtle.select(1)
    turlte.place()
    turtle.back()
end
end
--turtle.inspect() replacement
function turtle.inspect2()
  local success, block = turtle.inspect2()
  if block.name == nil then
    return nil
  else
    return block.name
  end
  end
--Moveforward and not wreck other turltes
local function moveforward()
  if turtle.inspect() == "minecraft:air" then
    turtle.forward()
  else
    for Forloop1= 1, 100 do
      turtle.detect()
     end
    moveforward()
   end
  end
  --Distance to go forward when at back
local MOVESIDE1DISTANCE = 1
--Direction to turn
local function MOVESIDE()
  turtle.left()
  end
--Distance to move on side.  
local MOVESIDE2DISTANCE = 10
--open redstone
local function MessageTrigger()
  local id,msg,dist=rednet.receive()  
end
--Other direction to turn
local function MOVESIDE2()
  if MOVESIDE() == turtle.left then
    turtle.left()
  else
    turtle.right()
end
PLACEANDBREAK()
end
local function Moveforwardallonce()
for Forloop2= 1, MOVESIDE1DISTANCE  do
moveforward()
end
MOVESIDE()
for Forloop3= 1, MOVESIDE2DISTANCE() do
moveforward()
end
MOVESIDE2()
for FORloop4= 1, MOVESIDE1DISTANCE() do
moveforward()
end
MOVESIDE()
end
--Running the program
--MessageTrigger()
--if messagme = 1 then
Moveforwardallonce()
