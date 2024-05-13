https://github.com/sveltejs/svelte/issues/11576

# Lighthouse results - original

| in seconds       | Total Blocking Time | SpeedIndex | First Contentful Paint | Largest Contentful Paint | Script Evaluation | Parse HTML & CSS |
|------------------|---------------------|------------|------------------------|--------------------------|-------------------|-----------------|
| Svelte 4 - Build | 4.3                 | 5.6        | 0.3                    | 16.6                     | **1.025**         | **1.516**       |
| Svelte 5 - Build | 12.15               | 14.2       | 0.3                    | 16.6                     | **1.942**         | **8.163**       |
| Vue - Build      | 11.22               | 12.5       | 0.3                    | 17.4                     | 2.247             | 7.050           |

# Lighthouse results - sample

| in seconds       | Total Blocking Time | SpeedIndex | First Contentful Paint | Largest Contentful Paint | Script Evaluation | Parse HTML & CSS |
|------------------|---------------------|------------|------------------------|--------------------------|-------------------|------------------|
| Svelte 4 - Build | 0                   | 1.9        | 1.3                    | 1.3                      | **0.208**         | 0.004            |
| Svelte 5 - Build | 0.810               | 1.7        | 0.3                    | 0.7                      | **0.358**         | 0.004            |
| Vue - Build      | 0.960               | 1.9        | 0.3                    | 0.9                      | 0.487             | 0.003            |
|                  |                     |            |                        |                          |                   |                  |
| Svelte 4 - Dev   | 9.92                | 12.1       | 0.8                    | 5.8                      | 9.242             |                  |
| Svelte 5 - Dev   | 1.450               | 2.6        | 0.8                    | 1.5                      | 0.644             |                  |
| Vue - Dev        | 3.110               | 4.4        | 0.7                    | 2.4                      | 1.528             |                  |


