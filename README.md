# Number-guessing-game

FINAL NOTE: I DONT WANT TO TAKE CREDITS FOR ANY OF THIS. I submited to github bc i thought this would be a real project. Turns out it was explained every single bit of the code in the page. So this was just a study thing. Anyways, it was interesting. Maybe in the future i make it pretty and add some things.

From this page https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash




What stopped me from doing the project by myself? I dont know how to interact with the HTML, so this is the main goal of this project.

This is some JS i did b4 starting to follow the tutorial


    function randomizer() {
        return 
    }
    function game(){
        let num = Math.floor(math.random() * 100) + 1;
        let guessList = []
        for(let lives = 1; i >= 10; i++){
            let input = null;
            if(input == num){
                console.log("Congrats! You won with " + lives + " tries out of 10!")
                return true;
            }else{
                guessList.push(input)
                console.log("You missed! :(")
                console.log(guessList)
                if(input > num){
                    console.log("Too high!")
                } else if(input < num){
                    console.log("Too low!")
                }


            }
        }
        return false;
    }



Finally, this is my first contact with methods like querySelector(), getElementById() and events. So this is my first contact of interaction between HTML and JS. I didn't just copy, obviously, i analyzed the code until i got a good understanding of everything. Great article :)