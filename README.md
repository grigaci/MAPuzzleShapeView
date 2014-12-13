#MAPuzzleShapeView
A rectangular view with puzzle shapes drawn on different sides.

##Installation
Drag and drop ```MAPuzzleShapeView.h/m``` into your project.

##Usage

``` objc
CGRect frame = CGRectMake(0.f, 0.f, 200.f, 100.f);

MAPuzzleShapeView puzzleShapeView = [[MAPuzzleShapeView alloc] initWithFrame:CGRectZero];
puzzleShapeView.shapeLength = 30.f;
puzzleShapeView.shapeAlignment = UIViewShapeAlignmentOnX;
puzzleShapeView.backgroundColor = [UIColor lightGrayColor];

[self.view addSubview:puzzleShapeView];
```

##Screenshot


![Screenshot](https://github.com/MadalinaArdelean/MAPuzzleShapeView/MAPuzzleShapeView/raw/master/screenshot1.png)
![Screenshot](https://github.com/MadalinaArdelean/MAPuzzleShapeView/MAPuzzleShapeView/raw/master/screenshot2.png)
