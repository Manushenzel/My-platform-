<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login to Goldmine</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-br from-blue-400 to-teal-400 min-h-screen flex items-center justify-center">
  <div class="bg-white rounded-2xl shadow-lg w-full max-w-sm p-6">
    <h2 class="text-xl font-semibold text-center mb-6">Login to Goldmine</h2>

    <form class="space-y-4">
      <div>
        <label class="block relative">
          <input type="email" placeholder="Email" class="pl-10 w-full py-2 rounded-lg bg-blue-50 focus:outline-none focus:ring-2 focus:ring-blue-500" />
          <span class="absolute left-3 top-2.5 text-blue-500">
            <!-- Email icon -->
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path d="M16 12l-4-4-4 4m0 0l4 4 4-4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </span>
        </label>
      </div>
      <div>
        <label class="block relative">
          <input type="password" placeholder="Password" class="pl-10 w-full py-2 rounded-lg bg-blue-50 focus:outline-none focus:ring-2 focus:ring-blue-500" />
          <span class="absolute left-3 top-2.5 text-blue-500">
            <!-- Lock icon -->
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path d="M12 15v2m0-6a2 2 0 012 2v2H10v-2a2 2 0 012-2z" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </span>
        </label>
      </div>
      <button type="submit" class="w-full bg-blue-600 text-white py-2 rounded-lg font-semibold hover:bg-blue-700">Login</button>
    </form>

    <div class="text-sm text-center mt-4">
      Don't Have An Account? <a href="#" class="text-blue-600 font-medium">Register</a>
    </div>
    <div class="text-sm text-center mt-2">
      <a href="#" class="text-blue-600">Reset password?</a>
    </div>

    <div class="mt-6 text-center">
      <p class="text-gray-500">Need Help?</p>
      <div class="mt-2 inline-block p-3 bg-blue-50 rounded-full">
        <!-- Phone icon -->
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path d="M3 5a2 2 0 012-2h3.6a1 1 0 01.95.684L11 7H5a2 2 0 00-2 2v9a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l1.45-4.316A1 1 0 0015.4 2H19a2 2 0 012 2v2" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
    </div>
  </div>
</body>
</html>
