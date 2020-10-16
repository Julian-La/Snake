# Snake rework
## [video link shows all possible outcomes](https://vimeo.com/468895598)
/**
 * This represents a version of the game Snake made with java.
 * In addition to the normal game mode, walls and a trap were added. 
 * Grid size = 16x16
 * The Player's start is fix.
 * Snake can move in four directions.
 * Snake loses velocity while growing.
 * Touching a purple bounty will add one tail unit to the snake.
 * Touching a blue trap will remove one tail unit. 
 * SCORE shows currently archived bounties, BEST shows highest score in runtime. 
 * Side note: walls were hardcoded, you can make it more interesting when setting walls at random.
 -> Making walls move did not work out. Snake got squashed too often. 
 * The sake's growth/decline will be handled in the class "Collision".
 * If desired, music will be added.
 */