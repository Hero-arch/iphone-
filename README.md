<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iPhone Giveaway - Claim Your Free iPhone Now!</title>
    <style>
        /* General Styles */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #f3f4f6, #e9ebef);
            color: #333333;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            color: #007BFF;
            margin-top: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }
        p {
            font-size: 1.2em;
            margin: 15px 0;
            line-height: 1.6;
            color: #555555;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }
        img:hover {
            transform: scale(1.05);
        }

        /* Button Styles */
        .button {
            display: inline-block;
            padding: 15px 30px;
            background: linear-gradient(90deg, #ff5722, #e64a19);
            color: #ffffff;
            font-size: 1.5em;
            text-decoration: none;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s, background 0.3s;
            margin: 10px;
        }
        .button:hover {
            background: linear-gradient(90deg, #e64a19, #d84315);
            transform: scale(1.1);
        }

        /* Share Button */
        .share-button {
            background: linear-gradient(90deg, #4caf50, #388e3c);
            margin: 20px 10px;
        }
        .share-button:hover {
            background: linear-gradient(90deg, #388e3c, #2e7d32);
        }

        /* Content Box */
        .content-box {
            background: #ffffff;
            border-radius: 20px;
            padding: 30px;
            margin: 30px auto;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            max-width: 600px;
        }

        /* Footer */
        footer {
            margin-top: 50px;
            font-size: 0.9em;
            color: #666666;
        }
    </style>
</head>
<body>
    <div class="content-box">
        <h1>🎉 Exclusive iPhone Giveaway 🎉</h1>
        <p>Congratulations! You've been selected for an exclusive chance to win a brand-new iPhone.</p>
        <img src="https://www.apple.com/newsroom/images/product/iphone/geo/Apple_iPhone-13-Pro_iPhone-13-Pro-Max_GEO_09142021_inline.jpg.slideshow-large_2x.jpg" alt="iPhone Giveaway">
        <p>Click the button below to claim your prize before it’s too late:</p>
        <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank" class="button">Claim Your iPhone Now</a>
        <button class="button share-button" id="copyButton">Copy Link</button>
        <p style="font-size: 0.9em; color: #888888; margin-top: 20px;">*Limited-time offer. Terms and conditions apply.</p>
    </div>
    <footer>
        <p>© 2024 iPhone Giveaway Inc. All rights reserved.</p>
        <p style="font-size: 0.8em;">This promotion is not affiliated with Apple Inc.</p>
    </footer>

    <script>
        // JavaScript for Copy Link Functionality
        document.getElementById('copyButton').addEventListener('click', function() {
            // Dynamically get the current page URL
            const linkToCopy = window.location.href;
            
            // Copying the link to clipboard
            navigator.clipboard.writeText(linkToCopy).then(() => {
                alert("Website link copied to clipboard!");
            }).catch(err => {
                alert("Failed to copy link: " + err);
            });
        });
    </script>
</body>
</html>