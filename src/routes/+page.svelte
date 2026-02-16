<script>
	import introImage from '$lib/assets/intro_1280@1x.png';
	import logo from '$lib/assets/qt_128@1x.png';
</script>

<div class="min-h-screen bg-gradient-to-b from-gray-50 to-white">
	<!-- Hero Section -->
	<section class="container mx-auto px-6 py-20">
		<div class="max-w-4xl mx-auto text-center">
			<div class="flex flex-col md:flex-row items-center justify-center gap-4 mb-6">
				<img src={logo} alt="QuickTabs Logo" class="w-32 h-32" />
				<h1 class="text-5xl md:text-6xl font-bold text-gray-900 tracking-tight">
					QuickTabs
				</h1>
			</div>
			<p class="text-xl text-gray-600 mb-8 leading-relaxed max-w-2xl mx-auto">
				一款 macOS 原生应用，类似 <kbd class="px-2 py-1 bg-gray-100 rounded text-sm font-mono">⌘+Tab</kbd> 切换应用，但更强大。
				QuickTabs 在原有基础上增加了编号，唤起应用列表后，直接按编号即可快速切换应用。
			</p>

			<!-- App Store Download Button -->
			<a
				href="https://apps.apple.com/us/app/quicktabs/id6755926389?mt=12"
				target="_blank"
				rel="noopener noreferrer"
				class="inline-flex items-center gap-3 bg-black text-white px-6 py-3 rounded-xl hover:bg-gray-800 transition-colors group mb-12"
			>
				<svg class="w-8 h-8" viewBox="0 0 24 24" fill="currentColor">
					<path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/>
				</svg>
				<div class="flex flex-col items-start">
					<span class="text-xs leading-tight opacity-80">Download on the</span>
					<span class="text-lg font-semibold leading-tight -mt-0.5">App Store</span>
				</div>
			</a>

			<!-- App Screenshot -->
			<div class="mb-16 rounded-2xl shadow-2xl overflow-hidden bg-white p-4">
				<img
					src={introImage}
					alt="QuickTabs 应用界面"
					class="w-full h-auto rounded-lg"
				/>
			</div>
		</div>
	</section>

	<!-- Features Section -->
	<section class="container mx-auto px-6 py-16">
		<div class="max-w-5xl mx-auto">
			<h2 class="text-3xl font-bold text-center text-gray-900 mb-12">
				应用特点
			</h2>
			<div class="grid md:grid-cols-2 gap-8">
				<div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
					<div class="text-4xl mb-4">⚡</div>
					<h3 class="text-xl font-semibold text-gray-900 mb-3">
						Built Natively
					</h3>
					<p class="text-gray-600">
						原生构建，充分利用 macOS 系统能力，提供流畅的原生体验。
					</p>
				</div>

				<div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
					<div class="text-4xl mb-4">🚀</div>
					<h3 class="text-xl font-semibold text-gray-900 mb-3">
						Blazing Fast Speed
					</h3>
					<p class="text-gray-600">
						极速响应，瞬间切换应用，让你的工作流程更加高效。
					</p>
				</div>

				<div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
					<div class="text-4xl mb-4">🔒</div>
					<h3 class="text-xl font-semibold text-gray-900 mb-3">
						Secure & Private
					</h3>
					<p class="text-gray-600">
						安全私密，所有数据本地处理，保护你的隐私安全。
					</p>
				</div>

				<div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
					<div class="text-4xl mb-4">✨</div>
					<h3 class="text-xl font-semibold text-gray-900 mb-3">
						Intuitive Design
					</h3>
					<p class="text-gray-600">
						直观设计，简洁优雅的界面，轻松上手，提升使用体验。
					</p>
				</div>
			</div>
		</div>
	</section>

	<!-- Usage Instructions Section -->
	<section class="container mx-auto px-6 py-16">
		<div class="max-w-5xl mx-auto">
			<h2 class="text-3xl font-bold text-center text-gray-900 mb-12">
				使用说明
			</h2>
			<div class="grid md:grid-cols-3 gap-8">
				<div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
					<div class="text-4xl mb-4">⌨️</div>
					<h3 class="text-xl font-semibold text-gray-900 mb-3">
						快捷键唤起
					</h3>
					<p class="text-gray-600">
						默认 <kbd class="px-2 py-1 bg-gray-100 rounded text-sm font-mono">⌥+Tab</kbd> 唤起程序
					</p>
				</div>

				<div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
					<div class="text-4xl mb-4">⚙️</div>
					<h3 class="text-xl font-semibold text-gray-900 mb-3">
						快捷键设置
					</h3>
					<p class="text-gray-600">
						鼠标左键点击 statusbar 按钮进行快捷键设置
					</p>
				</div>

				<div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
					<div class="text-4xl mb-4">🚪</div>
					<h3 class="text-xl font-semibold text-gray-900 mb-3">
						退出程序
					</h3>
					<p class="text-gray-600">
						鼠标右键单击 statusbar 按钮退出
					</p>
				</div>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="border-t border-gray-200 mt-20">
		<div class="container mx-auto px-6 py-8">
			<div class="text-center text-gray-600">
				<p class="mb-2">联系我们</p>
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
