<script>
	import introImage from '$lib/assets/intro_1280@1x.png';
	import logo from '$lib/assets/qt_128@1x.png';
</script>

<div class="min-h-screen bg-gradient-to-b from-gray-50 to-white">
	<!-- Hero Section -->
	<section class="container mx-auto px-6 py-20">
		<div class="max-w-4xl mx-auto text-center">
			<div class="flex flex-col md:flex-row items-center justify-center gap-4 mb-6">
				<img src={logo} alt="QuickTab Logo" class="w-32 h-32" />
				<h1 class="text-5xl md:text-6xl font-bold text-gray-900 tracking-tight">
					QuickTab
				</h1>
			</div>
			<p class="text-xl text-gray-600 mb-12 leading-relaxed max-w-2xl mx-auto">
				一款 macOS 原生应用，类似 <kbd class="px-2 py-1 bg-gray-100 rounded text-sm font-mono">⌘+Tab</kbd> 切换应用，但更强大。
				QuickTab 在原有基础上增加了数字编号，唤起应用列表后，直接按数字即可快速切换应用。
			</p>

			<!-- App Screenshot -->
			<div class="mb-16 rounded-2xl shadow-2xl overflow-hidden bg-white p-4">
				<img
					src={introImage}
					alt="QuickTab 应用界面"
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
