<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WattupUSA - Post-Pitch Leave Behind</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', sans-serif;
            background: #f9fafb;
            line-height: 1.5;
            color: #1f2937;
        }

        .brochure {
            width: 8.5in;
            height: 11in;
            margin: 20px auto;
            background: #ffffff;
            box-shadow: 0 10px 40px rgba(0,0,0,0.08);
            display: grid;
            grid-template-rows: auto 1fr auto;
            overflow: hidden;
            border-radius: 8px;
        }

        /* PROFESSIONAL HEADER */
        .header {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #0f172a 100%);
            color: white;
            padding: 1.5rem 2.5rem;
            text-align: center;
            border-bottom: 3px solid #38bdf8;
        }

        .header h1 {
            font-size: 1.75rem;
            font-weight: 900;
            margin: 0;
            line-height: 1.2;
            letter-spacing: -0.03em;
        }

        .header .subheading {
            font-size: 0.85rem;
            font-weight: 600;
            margin-top: 0.4rem;
            color: #cbd5e1;
            letter-spacing: 0.05em;
        }

        /* MAIN CONTENT */
        .content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.75rem;
            padding: 1.5rem 2rem;
            background: #ffffff;
            overflow-y: auto;
        }

        .column {
            display: flex;
            flex-direction: column;
            gap: 1.25rem;
        }

        .column-left {
            border-right: 3px solid #f0f4f8;
            padding-right: 1.5rem;
        }

        /* SECTION STYLING */
        .section {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .section h3 {
            font-size: 0.8rem;
            font-weight: 800;
            color: #0f172a;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            padding-bottom: 0.4rem;
            border-bottom: 2px solid #38bdf8;
        }

        /* KEY TAKEAWAYS */
        .key-takeaways {
            background: linear-gradient(135deg, #fef3c7 0%, #fef9e7 100%);
            border-left: 4px solid #f59e0b;
            padding: 0.9rem;
            border-radius: 6px;
        }

        .key-takeaways .takeaway-item {
            font-size: 0.78
