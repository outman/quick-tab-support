<script>
	import logo from '$lib/assets/qt_128@1x.png';
	import { base } from '$app/paths';
</script>

<div class="min-h-screen bg-gradient-to-b from-gray-50 to-white">
	<!-- Header -->
	<section class="container mx-auto px-6 py-12">
		<div class="max-w-4xl mx-auto">
			<div class="flex items-center justify-center gap-4 mb-8">
				<img src={logo} alt="QuickTabs Logo" class="w-16 h-16" />
				<h1 class="text-4xl md:text-5xl font-bold text-gray-900 tracking-tight">
					Privacy Policy
				</h1>
			</div>
		</div>
	</section>

	<!-- Privacy Content -->
	<section class="container mx-auto px-6 pb-20">
		<div class="max-w-4xl mx-auto">
			<div class="bg-white rounded-2xl shadow-lg border border-gray-100 p-8 md:p-12">
				<!-- Your Privacy Matters to Us -->
				<div class="mb-12">
					<h2 class="text-3xl font-bold text-gray-900 mb-6">
						Your Privacy Matters to Us
					</h2>
					<p class="text-gray-700 leading-relaxed text-lg">
						At QuickTabs, we are committed to protecting your privacy and ensuring the security of your personal information. We understand that privacy is a fundamental right, and we have designed our application with your privacy as a top priority. This privacy policy explains how we handle your data and what you can expect when using QuickTabs.
					</p>
				</div>

				<!-- No Data Collection -->
				<div class="mb-12">
					<h2 class="text-3xl font-bold text-gray-900 mb-6">
						No Data Collection
					</h2>
					<p class="text-gray-700 leading-relaxed mb-4">
						QuickTabs operates entirely on your local device. We do not collect, store, or transmit any personal information, usage data, or analytics. Specifically:
					</p>
					<ul class="list-disc list-inside text-gray-700 leading-relaxed space-y-2 ml-4">
						<li>No personal information is collected or stored</li>
						<li>No usage analytics or tracking data is gathered</li>
						<li>No application logs or diagnostic information is transmitted</li>
						<li>No user preferences or settings are sent to external servers</li>
						<li>All application data remains on your local machine</li>
					</ul>
					<p class="text-gray-700 leading-relaxed mt-4">
						Everything you do with QuickTabs stays on your device. We have no servers, no databases, and no way to access your information even if we wanted to.
					</p>
				</div>

				<!-- No Data Sharing -->
				<div class="mb-12">
					<h2 class="text-3xl font-bold text-gray-900 mb-6">
						No Data Sharing
					</h2>
					<p class="text-gray-700 leading-relaxed mb-4">
						Since we do not collect any data, there is nothing to share. QuickTabs does not:
					</p>
					<ul class="list-disc list-inside text-gray-700 leading-relaxed space-y-2 ml-4">
						<li>Share data with third parties</li>
						<li>Sell user information to advertisers or data brokers</li>
						<li>Use third-party analytics services</li>
						<li>Integrate with advertising networks</li>
						<li>Participate in any data sharing agreements</li>
					</ul>
					<p class="text-gray-700 leading-relaxed mt-4">
						Your privacy is protected by design. There is no data pipeline, no network requests, and no external communication beyond what is necessary for the application to function on your Mac.
					</p>
				</div>

				<!-- Legal Compliance -->
				<div class="mb-12">
					<h2 class="text-3xl font-bold text-gray-900 mb-6">
						Legal Compliance
					</h2>
					<p class="text-gray-700 leading-relaxed mb-4">
						QuickTabs is designed to comply with major privacy regulations, including:
					</p>
					<ul class="list-disc list-inside text-gray-700 leading-relaxed space-y-2 ml-4">
						<li><strong>GDPR (General Data Protection Regulation):</strong> As we do not collect or process personal data, QuickTabs naturally complies with GDPR requirements.</li>
						<li><strong>CCPA (California Consumer Privacy Act):</strong> Since no personal information is collected, there is no data to disclose, delete, or opt-out of.</li>
						<li><strong>PIPEDA (Personal Information Protection and Electronic Documents Act):</strong> Our zero-data-collection approach ensures compliance with Canadian privacy laws.</li>
					</ul>
					<p class="text-gray-700 leading-relaxed mt-4">
						If you have any questions about our compliance with specific privacy regulations, please feel free to contact us using the information provided below.
					</p>
				</div>

				<!-- Contact Information -->
				<div class="mb-8">
					<h2 class="text-3xl font-bold text-gray-900 mb-6">
						Contact Information
					</h2>
					<p class="text-gray-700 leading-relaxed mb-4">
						If you have any questions, concerns, or requests regarding this privacy policy or how QuickTabs handles your information, please contact us:
					</p>
					<div class="bg-gray-50 rounded-lg p-8 border border-gray-200">
						<p class="text-gray-700 mb-2">
							<strong>Email:</strong>
							<a
								href="mailto:pochonlee@gmail.com"
								class="text-blue-600 hover:text-blue-700 font-medium transition-colors ml-2"
							>
								pochonlee#gmail.com
							</a>
						</p>
						<p class="text-gray-700 text-sm mt-4">
							We will respond to your inquiries as soon as possible, typically within 48 hours.
						</p>
					</div>
				</div>

				<!-- Last Updated -->
				<div class="pt-8">
					<p class="text-sm text-gray-500">
						Last updated: November 30, 2025
					</p>
				</div>
			</div>

			<!-- Back to Home Link -->
			<div class="text-center mt-8">
				<a
					href="{base}/"
					class="inline-flex items-center text-blue-600 hover:text-blue-700 font-medium transition-colors"
				>
					← Back to Home
				</a>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="border-t border-gray-200 mt-20">
		<div class="container mx-auto px-6 py-8">
			<div class="text-center text-gray-600">
				<p class="mb-2">Contact Us</p>
				<a
					href="mailto:pochonlee@gmail.com"
					class="text-blue-600 hover:text-blue-700 font-medium transition-colors"
				>
					pochonlee#gmail.com
				</a>
				<p class="mt-6 text-sm text-gray-500">
					© {new Date().getFullYear()} Scrapmind All rights reserved.
				</p>
			</div>
		</div>
	</footer>
</div>

