# Latent-Actions-Cont
Contains example projects for the feature contained in [this pull request](https://github.com/EpicGames/UnrealEngine/pull/1752)

TestLatent Scene - The level blueprint demonstrates calling several latent actions from functions
  
TestCont Scene - Shows how to use Continuations to turn MediaPlayer::OpenURL into a latent action using only blueprints. Note that OpenURL is still synchronous in 4.10, but is now async in the Master branch. For this reason the async OnMediaOpened event is simulated with Delay.

