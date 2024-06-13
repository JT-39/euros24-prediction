# Predicting the results of the Euros 2024

This is python code which tries to predict the results of the 2024 Euros football competition in Germany.

Full credit for the code must go to Mihir Gharat, whom shared this code on Linkedin (link [here](https://www.linkedin.com/posts/mihirgharat211097_python-code-for-euros2024-prediction-activity-7180997560973594624-kfI9/)).

## Details

- Historic data on the results of previous Euros tournaments is pulled from Wikipedia.
- These are used to create a team strength indicator (average goals scored/ conceded for home/ away).
- Expected goals is calculated and a poisson distribution used to estimate goal probabilities, the point outcomes for each game is calculated.
- This is then used across the group stages and knockouts to find the winners.

## Collaborating

Clone the repository or copy the code, and find out who is predicted to win the tournament!

And... where do England finish?
