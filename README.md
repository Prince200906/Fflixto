Fflix - Free HD movies
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fflix - Watch Free Movies & TV Shows</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* Header */
        .header {
            background-color: black;
            padding: 15px;
            text-align: center;
        }

        .header h1 {
            font-size: 32px;
            font-weight: bold;
        }

        .header span {
            color: red;
        }

        /* Section Styling */
        .section {
            padding: 30px 20px;
            max-width: 900px;
            margin: auto;
            text-align: left;
        }

        .section h2 {
            font-size: 26px;
            font-weight: bold;
        }

        .section p {
            font-size: 16px;
            line-height: 1.6;
            color: #cccccc;
        }

        .italic {
            font-style: italic;
            font-weight: bold;
            color: lightgray;
        }

        /* Movie Image */
        .hero-image {
            width: 100%;
            max-width: 900px;
            border-radius: 8px;
            margin-top: 15px;
        }

        /* Movie Gallery */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }

        .gallery img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        /* Responsive */
        @media (max-width: 600px) {
            .section h2 {
                font-size: 22px;
            }
            .gallery {
                grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        <h1><span>Fflix</span> - Watch Free Movies & TV Shows</h1>
    </div>

    <!-- About Section -->
    <div class="section">
        <h2>What Is Fflix?</h2>
        <p>
            Fflix is a free online streaming platform offering an extensive selection of movies and TV shows across various genres. 
            Designed for viewers who value 
            convenience and quality, Fflix allows users to enjoy the latest Hollywood hits and beloved classics
            without the need for sign-ups or subscriptions.
        </p>
        <p>
            With a user-friendly interface, high-quality streaming, and a constantly updated content library, 
            Fflix is your go-to destination for non-stop entertainment. Whether you're in the mood for a blockbuster, a hidden gem,
            or a binge-worthy series, Fflix delivers an immersive viewing experience tailored to your preferences.

    <!-- Movie Collection Section -->
    <div class="section">
        <h2>Watch Fflix Movies Free Online HD</h2>
        <p class="italic">Extensive HD Movie Library</p>
        <p>
            Fflix provides a vast collection of high-definition movies across all genres, from thrilling blockbusters to heartwarming dramas. 
            Whether you’re in the mood for a recent release or a timeless classic, Fflix offers a diverse range of options, all available in stunning HD quality.
        </p>
    </div>

          <h2>Latest Movies</h2>
    <div class="gallery">
        <img
import openai

# Set up the OpenAI API key
openai.api_key = 'your-openai-api-key'

# Function to generate an image based on a prompt
def generate_image(prompt):
    response = openai.Image.create(
        prompt=prompt,
        n=1,
        size="1024x1024"
    )
    return response['data'][0]['url']

# Define the prompt for the images
prompts = [
    "A futuristic sci-fi city at night, glowing with neon lights and towering skyscrapers, depicting a bustling metropolis with flying cars.",
    "A group of adventurers standing on a cliff overlooking a vast jungle with an ancient temple in the distance, showcasing a sense of mystery and discovery.",
    "A medieval fantasy battle scene with knights in shining armor clashing with mythical creatures in a lush, green forest. The setting is dramatic, filled with action and high fantasy elements."
]

# Generate images based on the prompts
image_urls = [generate_image(prompt) for prompt in prompts]

# Display the generated URLs
for idx, url in enumerate(image_urls, 1):
    print(f"Image {idx}: {url}")


PRINCE CELMAR 10-SR
