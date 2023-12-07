/* Copy Animation */

.copyInput {
	display: inline-block;
	line-height: 50px;
	position: absolute;
	top: 0;
	right: 0;
	width: 40px;
	text-align: center;
	font-size: 14px;
	cursor: pointer;
	-webkit-transition: all .3s;
	-o-transition: all .3s;
	transition: all .3s;
  }

  .copied::after {
	position: absolute;
	top: 8px;
	right: 12%;
	width: 100px;
	display: block;
	content: "COPIED";
	font-size: 1em;
	padding: 5px 5px;
	color: #fff;
	background-color: hsl(var(--base));
	border-radius: 3px;
	opacity: 0;
	will-change: opacity, transform;
	animation: showcopied 1.5s ease;
 }
 
  @keyframes showcopied {
	0% {
		opacity: 0;
		transform: translateX(100%);
	}
	50% {
		opacity: 0.7;
		transform: translateX(40%);
	}
	70% {
		opacity: 1;
		transform: translateX(0);
	}
	100% {
		opacity: 0;
	}
  }

.input-group-text.copytext.copyBoard {
    cursor: pointer;
}




.cookies-card {
  width: 520px;
  padding: 30px;
  color: #dddddd;
  position: fixed;
  bottom: 15px;
  left: 15px;
  z-index: 999999;
  transition: all .5s;
  background: #222222;
  border-radius: 5px;
  border: 2px solid hsl(var(--base)/ 0.5);
  border-radius: 5px;
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  -ms-border-radius: 5px;
  -o-border-radius: 5px;
  background-color: var(--second_color);
  box-shadow: 0 0 15px hsl(var(--base)/ 0.5);
}

   
  .cookies-card.hide{
	bottom: -500px !important;
  }
  .radius--10px {
	border-radius: 10px;  

  .cookies-card__icon {
	width: 55px;
	height: 55px;
	border-radius: 50%;
	background-color: #6e6f70;
    color: #fff;
	font-size: 32px;
	display: inline-flex;
	justify-content: center;
	align-items: center;
  }
