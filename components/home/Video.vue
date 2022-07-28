<template>
    <div>
        <section id="video">
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <div class="videoWrapper">
                            <div class="circle pulse"></div>
                                <div class="circle">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 595.3 553.8" data-toggle="modal" data-target="#videoModal">
                                        <defs></defs>
                                        <g>
                                            <path d="M297.9 12.4C440 5.9 568.4 136 564 282.5 559.6 427.4 444.1 544 296.5 543.9 149.6 543.7 32.4 425.2 31.2 278 30 124.3 163.6 5.6 297.9 12.4zm-.3 22.2c-133.5-.2-242 107.9-242.5 241.6-.5 135.6 106.3 243.5 241.6 244.1 134.9.6 243.4-107 244-242.1.8-134-108.6-243.5-243.1-243.6z"></path>
                                            <path d="M328.5 274c-32.1-30.1-63.8-59.4-94.9-89.3-6.3-6-12.6-13.5-15.2-21.5-5.1-15.8.1-30.1 14.3-39.5 15-9.8 30.7-9 43.4 3.5 43.1 42.2 85.9 84.8 128 128.1 13.8 14.2 13.8 32-.1 46.3-42.1 43.3-84.7 86-128 128-14.4 14-34.7 12.3-48.2-1-14.2-14-15.2-34.1-.5-49.7 27.2-29 55.4-57.1 83.1-85.6 4.6-4.8 9.2-9.8 18.1-19.3z"></path>
                                        </g>
                                    </svg>
                                </div>
                            </div>
                        </div>
                    </div>
            </div>
			<div class="modal fade" id="videoModal" tabindex="-1" role="dialog" aria-labelledby="videoModal" aria-hidden="true">
				<div class="modal-dialog modal-xl modal-dialog-centered" role="document">
					<div class="modal-content">
						<div class="embed-responsive embed-responsive-16by9">
							<iframe class="embed-responsive-item" src="https://www.youtube.com/embed/2eR5LRs5apo" allowfullscreen=""></iframe>
						</div>
					</div>
				</div>
			</div>
        </section>
    </div>
</template>

<script>
export default {
  name: 'Video'
}
</script>

<style>
#video{
  background: url("assets/video.jpg") no-repeat;
  height: 100%;
}
#video .videoWrapper {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	text-align: center;
	min-height: 90vh;
}

#video .videoWrapper .circle {
	width: 200px;
	height: 200px;
	position: absolute;
	padding-top: 8px;
	border-radius: 50%;
	background-color: transparent;
	transform: scale(1, 1);
}

#video .videoWrapper .circle.pulse {
	position: relative;
	animation-timing-function: ease;
	animation: pulse 2s infinite;
}

#video .videoWrapper .pulse {
	position: relative;
	width: 150px;
	height: 150px;
	background-color: transparent;
	color: #0076ff;
	border-radius: 50%;
	text-align: center;
	line-height: 80px;
	font-size: 25px;
	-webkit-animation: pulse 0.3s infinite;
  }
  
  #video .videoWrapper .pulse::before,
  #video .videoWrapper .pulse::after {
	content: "";
	display: block;
	position: absolute;
	border: 1px solid #fff;
	left: -20px;
	right: -20px;
	top: -20px;
	bottom: -20px;
	border-radius: 50%;
	animation: animate 1.5s linear infinite;
	backface-visibility: hidden;
  }
  
  #video .videoWrapper .pulse::after {
	animation-delay: 0.5s;
  }

#video .videoWrapper svg {
	fill: #fff;
	stroke: none;
	stroke-linejoin: round;
	stroke-width: 5;
	transition: all 0.3s;
}

#video .videoWrapper svg:hover {
	cursor: pointer;
	fill: #fff;
	stroke: none;
	transform: scale(1.2, 1.2);
}

@keyframes animate {
	0% {
	  transform: scale(0.5);
	  opacity: 0;
	}
	50% {
	  opacity: 1;
	}
	100% {
	  transform: scale(1.2);
	  opacity: 0;
	}
  }
  
  
  @-webkit-keyframes pulse {
	0% {
	  -moz-transform: scale(0.9);
	  -ms-transform: scale(0.9);
	  -webkit-transform: scale(0.9);
	  transform: scale(0.9);
	}
	70% {
	  -moz-transform: scale(1);
	  -ms-transform: scale(1);
	  -webkit-transform: scale(1);
	  transform: scale(1);
	  box-shadow: 0 0 0 50px rgba(90, 153, 212, 0);
	}
	100% {
	  -moz-transform: scale(0.9);
	  -ms-transform: scale(0.9);
	  -webkit-transform: scale(0.9);
	  transform: scale(0.9);
	  box-shadow: 0 0 0 0 rgba(90, 153, 212, 0);
	}
  }


#video .modal {
  overflow-y: hidden !important;
}

#video .modal-dialog {
  max-width: 1280px;
  margin: 30px auto;
}

#video .modal-body {
position:relative;
padding:0px;
}
</style>