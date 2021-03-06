---
title: "Users and Organizations"
---

<nav class="application-bar application-bar-dark navbar navbar-expand-md">
	<div class="container-fluid container-fluid-max-xl">
		<ul class="navbar-nav">
			<li class="nav-item">
				<a class="nav-link nav-link-monospaced" href="#1">
					<svg class="lexicon-icon lexicon-icon-product-menu-closed" focusable="false" role="presentation">
						<use href="/images/icons/icons.svg#product-menu-closed" />
					</svg>
				</a>
			</li>
		</ul>
		<h1 class="navbar-title navbar-text-truncate">Users and Organizations</h1>
		<ul class="navbar-nav">
			<li class="dropdown nav-item">
				<a aria-expanded="false" aria-haspopup="true" class="dropdown-toggle nav-link nav-link-monospaced" data-toggle="dropdown" href="#1" role="button">
					<svg class="lexicon-icon lexicon-icon-ellipsis-v" focusable="false" role="presentation">
						<use href="/images/icons/icons.svg#ellipsis-v" />
					</svg>
				</a>
				<ul aria-labelledby="navbarDropdownMenuLink" class="dropdown-menu dropdown-menu-right">
					<li><a class="dropdown-item" href="#1">Action</a></li>
					<li><a class="dropdown-item" href="#1">Another action</a></li>
					<li><a class="dropdown-item" href="#1">Something else here</a></li>
					<li class="dropdown-divider"></li>
					<li><a class="dropdown-item" href="#1">Separated link</a></li>
				</ul>
			</li>
		</ul>
	</div>
</nav>

<nav class="navbar navbar-collapse-absolute navbar-expand-md navbar-underline navigation-bar navigation-bar-secondary">
	<div class="container-fluid container-fluid-max-xl">
		<a aria-controls="navigationBarCollapse01" aria-expanded="false" aria-label="Toggle Navigation" class="collapsed navbar-toggler navbar-toggler-link" data-toggle="collapse" href="#navigationBarCollapse01" role="button">
			<span class="navbar-text-truncate">Users</span>
			<svg class="lexicon-icon lexicon-icon-caret-bottom" focusable="false" role="presentation">
				<use href="/images/icons/icons.svg#caret-bottom" />
			</svg>
		</a>
		<div class="collapse navbar-collapse" id="navigationBarCollapse01">
			<div class="container-fluid container-fluid-max-xl">
				<ul class="navbar-nav">
					<li class="nav-item">
						<a class="active nav-link" href="#1">
							<span class="navbar-text-truncate">Users</span>
						</a>
					</li>
					<li aria-label="Current Page" class="nav-item">
						<a class="nav-link" href="#1">
							<span class="navbar-text-truncate">Organizations</span>
						</a>
					</li>
				</ul>
			</div>
		</div>
	</div>
</nav>

<div class="page-header">
	<div class="container-fluid container-fluid-max-xl">
		<ol class="breadcrumb">
			<li class="breadcrumb-item">
				<a class="breadcrumb-link" href="#1" title="Home">
					<span class="breadcrumb-text-truncate">Home</span>
				</a>
			</li>
			<li class="active breadcrumb-item">
				<span class="breadcrumb-text-truncate" title="John Doe">John Doe</span>
			</li>
		</ol>
		<h2>John Doe</h2>
		<ul class="nav nav-underline">
			<li class="nav-item"><a class="active nav-link" href="#1">User Information</a></li>
			<li class="nav-item"><a class="nav-link" href="#1">Identification</a></li>
			<li class="nav-item"><a class="nav-link" href="#1">Miscellaneous</a></li>
		</ul>
	</div>
</div>

<div class="alert alert-danger alert-dismissible alert-fluid" role="alert">
	<div class="container-fluid container-fluid-max-xl">
		<svg class="lexicon-icon lexicon-icon-info-circle" focusable="false" role="presentation">
			<use href="/images/icons/icons.svg#info-circle"></use>
		</svg>
		<strong class="lead">Error:</strong> This is an error message.
		<button aria-label="Close" class="close" data-dismiss="alert" type="button">
			<svg class="lexicon-icon lexicon-icon-times" focusable="false" role="presentation">
				<use href="/images/icons/icons.svg#times" />
			</svg>
		</button>
	</div>
</div>

<div class="container-fluid container-fluid-max-xl container-form-lg">
	<div class="row">
		<div class="col-md-12">
			<form>
				<div class="sheet sheet-lg">
					<div class="alert alert-dismissible alert-info" role="alert">
						<svg class="lexicon-icon lexicon-icon-info-circle" focusable="false" role="presentation">
							<use href="/images/icons/icons.svg#info-circle"></use>
						</svg>
						<strong class="lead">Info:</strong> Street 1 and City are required fields. Postal Code could be required in some countries.
						<button aria-label="Close" class="close" data-dismiss="alert" type="button">
							<svg class="lexicon-icon lexicon-icon-times" focusable="false" role="presentation">
								<use href="/images/icons/icons.svg#times" />
							</svg>
						</button>
					</div>
					<div class="form-group-autofit">
						<div class="form-group-item">
							<label>
								Street 1
								<span class="reference-mark">
									<svg class="lexicon-icon lexicon-icon-asterisk" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#asterisk" />
									</svg>
								</span>
							</label>
							<input class="form-control" placeholder="Street 1" type="text" value="1400 Montefino Ave"/>
						</div>
						<div class="form-group-item">
							<label>
								Street 2
							</label>
							<input class="form-control" placeholder="Street 2" type="text"/>
						</div>
					</div>
					<div class="form-group-autofit">
						<div class="form-group-item">
							<label>
								City
								<span class="reference-mark">
									<svg class="lexicon-icon lexicon-icon-asterisk" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#asterisk" />
									</svg>
								</span>
							</label>
							<input class="form-control" placeholder="City" type="text" value="Diamond Bar"/>
						</div>
						<div class="form-group-item">
							<label>
								State
							</label>
							<input class="form-control" placeholder="State" type="text" value="CA"/>
						</div>
						<div class="form-group-item">
							<label>
								Postal Code
							</label>
							<input class="form-control" placeholder="Postal Code" type="text" value="91765"/>
						</div>
					</div>
					<h4 class="sheet-subtitle">Sheet Subtitle ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual</h4>
					<div class="form-group-autofit">
						<div class="form-group-item">
							<label>Input Label 1</label>
							<input class="form-control" type="text"/>
						</div>
					</div>
					<div class="form-group-autofit">
						<div class="form-group-item">
							<label>Input Label 2</label>
							<input class="form-control" type="text"/>
						</div>
					</div>
					<h5 class="sheet-tertiary-title">Sheet Tertiary Title</h5>
					<div class="form-group-autofit">
						<div class="form-group-item">
							<div class="custom-control custom-radio">
								<label>
									<input checked class="custom-control-input" id="radio1" name="radio" type="radio"/>
									<span class="custom-control-label">
										<span class="custom-control-label-text">Radio 1 Label</span>
									</span>
								</label>
							</div>
							<div class="custom-control custom-radio">
								<label>
									<input class="custom-control-input" id="radio2" name="radio" type="radio"/>
									<span class="custom-control-label">
										<span class="custom-control-label-text">Radio 2 Label</span>
									</span>
								</label>
							</div>
							<div class="custom-control custom-radio">
								<label>
									<input checked class="custom-control-input" id="radio3" name="radio" type="radio"/>
									<span class="custom-control-label">
										<span class="custom-control-label-text">Radio 3 Label</span>
									</span>
								</label>
							</div>
						</div>
					</div>
					<div aria-orientation="vertical" class="panel-group panel-group-flush" role="tablist">
						<div class="panel">
							<a aria-controls="accordion03CollapseTwo" aria-expanded="true" class="collapse-icon sheet-subtitle" data-toggle="collapse" href="#accordion03CollapseTwo" id="accordion03HeadingTwo" role="tab">
								<span class="panel-title">Password</span>
								<span class="collapse-icon-closed">
									<svg class="lexicon-icon lexicon-icon-angle-right" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-right" />
									</svg>
								</span>
								<span class="collapse-icon-open">
									<svg class="lexicon-icon lexicon-icon-angle-down" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-down" />
									</svg>
								</span>
							</a>
							<div aria-labelledby="accordion03HeadingTwo" class="panel-collapse collapse show" id="accordion03CollapseTwo" role="tabpanel">
								<div class="panel-body">
									<div class="form-group">
										<label>
											Current Password
											<span class="reference-mark">
												<svg class="lexicon-icon lexicon-icon-asterisk" focusable="false" role="presentation">
													<use href="/images/icons/icons.svg#asterisk" />
												</svg>
											</span>
										</label>
										<input class="form-control" placeholder="Current Password" type="password" value="my-secret"/>
									</div>
									<div class="form-group">
										<label>
											New Password
											<span class="reference-mark">
												<svg class="lexicon-icon lexicon-icon-asterisk" focusable="false" role="presentation">
													<use href="/images/icons/icons.svg#asterisk" />
												</svg>
											</span>
										</label>
										<input class="form-control" placeholder="New Password" type="password" value="my-new-secret"/>
									</div>
									<div class="form-group">
										<label>
											Confirm New Password
											<span class="reference-mark">
												<svg class="lexicon-icon lexicon-icon-asterisk" focusable="false" role="presentation">
													<use href="/images/icons/icons.svg#asterisk" />
												</svg>
											</span>
										</label>
										<input class="form-control" placeholder="Confirm New Password" type="password" value="my-new-secret"/>
									</div>
								</div>
							</div>
						</div>
						<div class="panel">
							<a aria-controls="accordion03CollapseOne" aria-expanded="false" class="collapse-icon collapsed sheet-subtitle" data-toggle="collapse" href="#accordion03CollapseOne" id="accordion03HeadingOne" role="tab">
								<span class="panel-title">Organizations</span>
								<span class="collapse-icon-closed">
									<svg class="lexicon-icon lexicon-icon-angle-right" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-right" />
									</svg>
								</span>
								<span class="collapse-icon-open">
									<svg class="lexicon-icon lexicon-icon-angle-down" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-down" />
									</svg>
								</span>
							</a>
							<div aria-labelledby="accordion03HeadingOne" class="panel-collapse collapse" id="accordion03CollapseOne" role="tabpanel">
								<div class="panel-body">
									In organic dripper so, body, robust medium pumpkin spice cup, in aged dripper latte extra cup white. And viennese redeye carajillo, beans, mug viennese, carajillo id breve decaffeinated americano crema chicory whipped arabica variety aged robusta. Affogato lungo eu, cultivar at, aged breve and blue mountain roast breve americano aged. Sugar acerbic sweet variety aged café au lait chicory, java, single shot percolator aromatic brewed wings, a, sugar, body, aftertaste organic barista espresso dripper to go. Flavour to go strong steamed mazagran trifecta decaffeinated percolator crema, aged americano rich chicory frappuccino foam white.
								</div>
							</div>
						</div>
						<div class="panel">
							<a aria-controls="accordion03CollapseThree" aria-expanded="false" class="collapse-icon collapsed sheet-subtitle" data-toggle="collapse" href="#accordion03CollapseThree" id="accordion03HeadingThree" role="tab">
								<span class="panel-title">ReallySuperInsanelyJustIncrediblyLongAndTotallyNotPossibleWordButWeAreReallyTryingToCoverAllOurBasesHereJustInCaseSomeoneIsNutsAsPerUsual User Groups</span>
								<span class="collapse-icon-closed">
									<svg class="lexicon-icon lexicon-icon-angle-right" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-right" />
									</svg>
								</span>
								<span class="collapse-icon-open">
									<svg class="lexicon-icon lexicon-icon-angle-down" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-down" />
									</svg>
								</span>
							</a>
							<div aria-labelledby="accordion03HeadingThree" class="panel-collapse collapse" id="accordion03CollapseThree" role="tabpanel">
								<div class="panel-body">
									Flavour filter fair trade kopi-luwak robusta viennese, trifecta grinder, grounds lungo beans, half and half cup steamed cappuccino cinnamon. Percolator, extra, strong, breve, french press to go aromatic half and half aroma barista caramelization ut froth breve spoon redeye to go skinny rich skinny spoon. As turkish est filter foam con panna, cinnamon, aroma grounds cup whipped cultivar extra. Latte bar crema cultivar espresso pumpkin spice viennese, body viennese milk variety dripper, spoon, blue mountain robusta cultivar et spoon. Macchiato id eu brewed, and mazagran cinnamon so wings, doppio mocha froth blue mountain froth half and half iced to go whipped single shot.
								</div>
							</div>
						</div>
						<div class="panel">
							<a aria-controls="accordion03CollapseFour" aria-expanded="false" class="collapse-icon collapsed sheet-subtitle" data-toggle="collapse" href="#accordion03CollapseFour" id="accordion03HeadingFour" role="tab">
								<span class="panel-title">Roles</span>
								<span class="collapse-icon-closed">
									<svg class="lexicon-icon lexicon-icon-angle-right" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-right" />
									</svg>
								</span>
								<span class="collapse-icon-open">
									<svg class="lexicon-icon lexicon-icon-angle-down" focusable="false" role="presentation">
										<use href="/images/icons/icons.svg#angle-down" />
									</svg>
								</span>
							</a>
							<div aria-labelledby="accordion03HeadingFour" class="panel-collapse collapse" id="accordion03CollapseFour" role="tabpanel">
								<div class="panel-body">
									Eu ristretto ut sugar rich saucer milk aftertaste, froth dark, cultivar blue mountain as coffee cappuccino. Saucer grounds mocha, aroma, half and half coffee eu robusta roast, doppio skinny galão, extraction, frappuccino aromatic breve crema frappuccino aroma. Froth half and half so java, grounds half and half, macchiato at est sugar mug redeye, strong, cream seasonal qui doppio robusta. Wings, at, cup dark, a, breve french press decaffeinated acerbic, black extra, and, saucer barista rich seasonal barista blue mountain. Roast mazagran a and id mug in est trifecta pumpkin spice coffee and mug trifecta, ut breve, mug frappuccino mug, breve mocha qui aged aftertaste.
								</div>
							</div>
						</div>
					</div>
				</div>
			</form>
		</div>
	</div>
</div>