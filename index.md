<!DOCTYPE html>
<html>
<head>
	<title>The Restaurant--Knight</title>
	<meta charset="UTF-8">
	<link rel="stylesheet" href="css/fenyechajian.css"/>
	<link rel="stylesheet" href="css/lunbotuchajian.css"/>
	<link rel="stylesheet" href="css/style.css"/>
</head>
<body>
	<!-- 菜单栏 -->
	<header class="header-section">
		<div class="header-warp">
			<div class="site-logo">
				<img src="img/logo.png">
			</div>
			<!-- responsive -->
			<div class="nav-switch">
				<i>更多</i>
			</div>
			<!-- menu -->
			<ul class="main-menu">
				<li><a href="index.html" class="active">主页</a></li>
				<li><a href="menu.html">菜单</a></li>
				<li><a href=" takeout.html">购物车</a></li>
			</ul>
			<div class="header-right">
				<p><span>联系我们</span>22331314</p>			
			</div>
		</div>
	</header>

	<!-- 主界面 -->
	<section class="hero-section">
		<div class="hero-slider owl-carousel">
			<div class="hs-item set-bg" data-setbg="img/轮播图用/slider-1.jpg">
				<div class="hs-content">
					<div class="hsc-warp">
						<h2>欢迎光临<span>.</span></h2>
					</div>
				</div>
			</div>
			<div class="hs-item set-bg" data-setbg="img/轮播图用/slider-2.jpg">
				<div class="hs-content">
					<div class="hsc-warp">
						<h2>我们有特别菜式<span>.</span></h2>
					</div>
				</div>
			</div>
			<div class="hs-item set-bg" data-setbg="img/轮播图用/slider-3.jpg">
				<div class="hs-content">
					<div class="hsc-warp">
						<h2>并且兼顾卫生<span>.</span></h2>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- 介绍栏 -->
	<section class="services-section spad">
		<div class="container">
			<div class="section-title">
				<div><img src="img/服务生.png"></div>
				<h2>我们可提供的服务</h2>
			</div>
			<div class="row services">
				<div class="col-lg-3 col-md-6 service-item">
					<div><img src="img/晚餐.png"></div>
					<h3>早餐</h3>
					<p>早餐要吃好.</p>
				</div>
				<div class="col-lg-3 col-md-6 service-item">
					<div><img src="img/晚餐.png"></div>
					<h3>午餐</h3>
					<p>午餐要吃饱.</p>
				</div>
				<div class="col-lg-3 col-md-6 service-item">
					<div><img src="img/晚餐.png"></div>
					<h3>晚餐</h3>
					<p>晚餐要吃少.</p>
				</div>
			</div>
		</div>
	</section>

	<!-- 菜单区 -->
	<section class="menu-section spad set-bg" data-setbg="img/menu-bg.jpg">
		<div class="container">
			<div class="section-title text-white">
				<div><img src="img/菜单白.png"></div>
				<h2>我们可提供的料理</h2>
			</div>
			<!-- menu tab nav -->
			<ul class="menu-tab-nav nav nav-tabs" role="tablist">
				<li class="nav-item">
					<a class="nav-link active" data-toggle="tab" href="#tab-1" role="tab" aria-controls="tab-1" aria-selected="true">早餐</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" data-toggle="tab" href="#tab-2" role="tab" aria-controls="tab-2" aria-selected="false">午餐</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" data-toggle="tab" href="#tab-3" role="tab" aria-controls="tab-3" aria-selected="false">晚餐</a>
				</li>
			</ul>
			<div class="tab-content menu-tab-content">
				<!-- single tab content -->
				<div class="tab-pane fade show active" id="tab-1" role="tabpanel" aria-labelledby="tab-1">
			<div class="row">
						<div class="col-lg-6">
							<!-- menu item -->
							<div class="menu-item">
								<h5>经典西式早餐</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>经典英式早餐</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>火腿蛋</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
						</div>
						<div class="col-lg-6">
							<!-- menu item -->
							<div class="menu-item">
								<h5>欧姆蛋</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>三明治</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>松饼</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>坚果牛奶</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
						</div>
			</div>
				</div>
				<!-- single tab content -->
				<div class="tab-pane fade" id="tab-2" role="tabpanel" aria-labelledby="tab-2">
					<div class="row">
						<div class="col-lg-6">
							<!-- menu item -->
							<div class="menu-item">
								<h5>惠灵顿牛排</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>奶油蘑菇汤</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>焗土豆泥</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>西班牙蒜蓉虾</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
						</div>
						<div class="col-lg-6">
							<!-- menu item -->
							<div class="menu-item">
								<h5>迷迭香烤薯角</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>意大利面</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>西班牙海鲜饭</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
						</div>
					</div>
				</div>
				<!-- single tab content -->
				<div class="tab-pane fade" id="tab-3" role="tabpanel" aria-labelledby="tab-3">
					<div class="row">
						<div class="col-lg-6">
							<!-- menu item -->
							<div class="menu-item">
								<h5>法棍罗宋汤</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>芝士焗大虾</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>天然酵种佛卡夏</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
						</div>
						<div class="col-lg-6">
							<!-- menu item -->
							<div class="menu-item">
								<h5>奶油蘑菇鸡</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>蘑菇培根焗饭</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>至尊披萨 </h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
							<!-- menu item -->
							<div class="menu-item">
								<h5>香橙黑蒜芥末虾球</h5>
								<div class="mi-meta">
									<div class="menu-price">9.00</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="text-center pt-5">
				<a href="#" class="site-btn">更多</a>
			</div>
		</div>
	</section>
	<!-- Menu section end -->
	<!--======js引用区======-->
	<script src="js/jquery-3.5.1.min.js"></script>
	<script src="js/fenyechajian.js"></script>
	<script src="js/lunbotuchajian.js"></script>
	<script src="js/main.js"></script>
    </body>
</html>
