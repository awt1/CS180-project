# CS180-project
Synopsis

We are going to create a game that sees a ball boucing around the screen.

Code Example

 //This is run before a new game (also after an old game)
    @Override
    public void setupBeginning() {
        //Initialise speeds
        mBallSpeedX = 0;
        mBallSpeedY = 0;

        //Place the ball in the middle of the screen.
        //mBall.Width() and mBall.getHeigh() gives us the height and width of the image of the ball
        mBallX = mCanvasWidth / 2;
        mBallY = mCanvasHeight / 2;
    }

    @Override
    protected void doDraw(Canvas canvas) {
        //If there isn't a canvas to draw on do nothing
        //It is ok not understanding what is happening here
        if(canvas == null) return;


Contributors

Andy Tatch,

Jac Jones,
Luke Thomas,
Jonathan Brayley,
