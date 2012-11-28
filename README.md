# GRButtons



## Usage

- import `QuartzCore` framework to your project
- import `GRButtons.h`

Examples:

Simple UIButton:
	[self.view addSubview:GRButton(GRTypeMailRect, 10, 160, 32, self, @selector(action:), [UIColor grayColor], GRStyleIn)];

UIBarButtonItem:
	UIBarButtonItem *button = [[UIBarButtonItem alloc] initWithCustomView:GRButton(GRTypeTwitter, 0, 0, 30, self, @selector(action:), color, GRStyleIn)];