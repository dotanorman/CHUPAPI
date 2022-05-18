class Car {
    constructor(cname, speed) {
	this.cname = cname;
	this.speed = speed;
	this.accelerate = function() {
	this.speed += 10;
	};
	this.brake = function() {
	this.speed -= 5;
	};
    };
	get speeds() {
	let currentspeed = this.speed / 1.6;
	return currentspeed + " mi/h";
	}
	get speedJS() {
	let current = this.speed / 1.6;
	let currentspeed = current * 1.6;
	return currentspeed + " mi/h";
	}
};

let BMW = new Car('BMW', 120);

console.log(BMW);
console.log('Speeds Getter');
console.log(BMW.speeds);
console.log('SpeedJS Getter');
console.log(BMW.speedJS);
console.log('Brake');
BMW.brake();
console.log(BMW);
console.log('Accelerate');
BMW.accelerate();
console.log(BMW);
