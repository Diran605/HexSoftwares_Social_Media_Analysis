# \# Social Media Analytics

# 

# Exploratory data analysis of social media activity across platforms, regions, and content types using Python.

# 

# \## Project Structure

# 

# ```

# ├── social\_anal.ipynb          # Main analysis notebook

# └── social\_media\_dataset.csv   # Dataset (1,000 posts)

# ```

# 

# \## Dataset Overview

# 

# The dataset contains \*\*1,000 social media posts\*\* with the following fields:

# 

# | Column | Type | Description |

# |---|---|---|

# | `post\_id` | string | Unique identifier for each post |

# | `platform` | string | Social media platform |

# | `hashtag` | string | Hashtag associated with the post |

# | `content\_type` | string | Format/type of the content |

# | `region` | string | Geographic region of the post |

# | `views` | integer | Number of views |

# | `likes` | integer | Number of likes |

# | `shares` | integer | Number of shares |

# | `comments` | integer | Number of comments |

# | `engagement\_level` | string | Categorical engagement label (Low / Medium / High) |

# 

# \*\*Platforms covered:\*\* YouTube, Instagram, X, TikTok, LinkedIn, Facebook

# 

# \*\*Content types:\*\* Live, Reel, Text, Carousel, Video, Image, Story, Poll

# 

# \*\*Regions:\*\* Southern Africa, East Africa, Central Africa, West Africa, North Africa, Latin America, Asia, Europe, North America, Middle East

# 

# \## Analysis Performed

# 

# The notebook (`social\_anal.ipynb`) covers four main areas:

# 

# \### 1. Platform-wise Analysis

# \- Pie chart of platform distribution — which platforms have the most posts in the dataset.

# 

# \### 2. Region-wise Platform Usage

# \- Stacked bar chart showing which platforms are used across each region.

# \- Per-region pie charts breaking down platform share for each geography.

# 

# \### 3. Engagement Analysis

# \- Region-wise total engagement (views, likes, shares, comments) on a log scale.

# \- Platform-wise total engagement comparison across all four engagement metrics.

# 

# \### 4. Region-wise Popular Content Types

# \- Stacked bar chart showing the most popular content formats per region.

# 

# \## Requirements

# 

# ```

# pandas

# matplotlib

# seaborn

# ```

# 

# Install with:

# 

# ```bash

# pip install pandas matplotlib seaborn

# ```

# 

# \## Usage

# 

# 1\. Place `social\_media\_dataset.csv` in the same directory as the notebook.

# 2\. Open `social\_anal.ipynb` in Jupyter Notebook or JupyterLab.

# 3\. Run all cells in order.

# 

# ```bash

# jupyter notebook social\_anal.ipynb

# ```

