<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elegant Reservation</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --gradient-start: #FF4D4D;
            --gradient-end: #D32F2F;
            --white: #FFFFFF;
            --text-color: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text-color);
            line-height: 1.6;
            padding: 1rem;
        }

        .reservation-container {
            width: 100%;
            max-width: 500px;
            background-color: var(--white);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            overflow: hidden;
            position: relative;
        }

        .reservation-header {
            background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
            color: var(--white);
            text-align: center;
            padding: 1.5rem;
            position: relative;
            z-index: 1;
        }

        .reservation-header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
            z-index: -1;
            opacity: 0.8;
        }

        .reservation-header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2rem;
            font-weight: 700;
            letter-spacing: 1px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .reservation-form {
            padding: 2rem;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 700;
            color: var(--gradient-end);
        }

        input, select {
            width: 100%;
            padding: 0.75rem;
            border: 2px solid var(--gradient-start);
            border-radius: 10px;
            font-size: 1rem;
            transition: all 0.3s ease;
        }

        input:focus, select:focus {
            outline: none;
            border-color: var(--gradient-end);
            box-shadow: 0 0 0 3px rgba(211, 47, 47, 0.2);
        }

        .btn {
            display: block;
            width: 100%;
            padding: 1rem;
            background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
            color: var(--white);
            border: none;
            border-radius: 10px;
            font-size: 1rem;
            font-weight: 700;
            letter-spacing: 1px;
            cursor: pointer;
            transition: all 0.3s ease;
            margin-top: 1rem;
            text-transform: uppercase;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 7px 20px rgba(0,0,0,0.2);
            filter: brightness(1.1);
        }

        .whatsapp-btn {
            background: linear-gradient(135deg, #25D366, #128C7E);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .whatsapp-btn img {
            width: 24px;
            margin-right: 10px;
        }

        #confirmationMessage {
            background: linear-gradient(135deg, #f0f0f0, #e0e0e0);
            border-left: 5px solid var(--gradient-end);
            padding: 1rem;
            margin-top: 1rem;
            border-radius: 5px;
            display: none;
        }

        @media (max-width: 600px) {
            .reservation-container {
                margin: 1rem;
                width: calc(100% - 2rem);
            }
        }
    </style>
</head>
<body>
    <div class="reservation-container">
        <div class="reservation-header">
            <h1>Reserve Your Table</h1>
        </div>
        <div class="reservation-form">
            <form id="reservationForm">
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" placeholder="John Doe" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" placeholder="johndoe@example.com" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" placeholder="+27 62 592 8143" required>
                </div>
                <div class="form-group">
                    <label for="date">Reservation Date</label>
                    <input type="date" id="date" required>
                </div>
                <div class="form-group">
                    <label for="time">Reservation Time</label>
                    <input type="time" id="time" required>
                </div>
                <div class="form-group">
                    <label for="guests">Number of Guests</label>
                    <select id="guests" required>
                        <option value="">Select Number of Guests</option>
                        <option value="1">1 Person</option>
                        <option value="2">2 People</option>
                        <option value="3">3 People</option>
                        <option value="4">4 People</option>
                        <option value="5">5 People</option>
                        <option value="6">6+ People</option>
                    </select>
                </div>
                <button type="submit" class="btn">Book Reservation</button>
                <button type="button" id="whatsappBtn" class="btn whatsapp-btn">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
                    Send Booking via WhatsApp
                </button>
            </form>
            <div id="confirmationMessage"></div>
        </div>
    </div>

    <script>
        document.getElementById('reservationForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Collect form data
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const phone = document.getElementById('phone').value;
            const date = document.getElementById('date').value;
            const time = document.getElementById('time').value;
            const guests = document.getElementById('guests').value;
            
            // Simple validation
            if (!name || !email || !phone || !date || !time || !guests) {
                alert('Please fill in all fields');
                return;
            }
            
            // Create confirmation message
            const confirmationMessage = document.getElementById('confirmationMessage');
            confirmationMessage.innerHTML = `
                <strong>Reservation Confirmed!</strong><br>
                Name: ${name}<br>
                Email: ${email}<br>
                Phone: ${phone}<br>
                Date: ${date}<br>
                Time: ${time}<br>
                Guests: ${guests}
            `;
            confirmationMessage.style.display = 'block';
            
            // Prepare WhatsApp message
            const whatsappMessage = encodeURIComponent(`Reservation Details:
Name: ${name}
Email: ${email}
Phone: ${phone}
Date: ${date}
Time: ${time}
Guests: ${guests}`);
            
            // Update WhatsApp button
            const whatsappBtn = document.getElementById('whatsappBtn');
            whatsappBtn.onclick = function() {
                window.open(`https://wa.me/27625928143?text=${whatsappMessage}`, '_blank');
            };
        });

        // Prevent past dates
        const today = new Date().toISOString().split('T')[0];
        document.getElementById('date').setAttribute('min', today);
    </script>
</body>
</html>
