# GRButtons

- create social network buttons without any image
- easy to embed into any project, two files are needed

Avaliable buttons:
- Facebook
- Twitter
- Google+
- Pinterest
- Dribble
- Flickr
- Email

<img src="https://github.com/GRButtons/raw/master/buttons_screenshot.png" alt="GRButtons" title="GRButtons" style="display:block; margin: 10px auto 30px auto;" class="center">

## Usage

- add&import `QuartzCore` framework to your project
- add `GRButtons.h` and `GRButons.m` to your project
- import `GRButtons.h`

#Examples:

Simple UIButton:

	[self.view addSubview:GRButton(GRTypeMailRect, 10, 160, 32, self, @selector(action:), [UIColor grayColor], GRStyleIn)];

UIBarButtonItem:

	UIBarButtonItem *button = [[UIBarButtonItem alloc] initWithCustomView:GRButton(GRTypeTwitter, 0, 0, 64, self, @selector(action:), color, GRStyleIn)];