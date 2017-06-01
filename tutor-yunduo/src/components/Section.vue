<template>
	<div id="section">
		<div class="section">
			<!--search-->
			<div class="search">
				<img src="../assets/img/techer_07.jpg"/>
				<input type="search" placeholder="输入你要查找的导师姓名" />
			</div>
			
			<!--follow-->
			<div class="follow" @click='show()'>
				<span>我关注的</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--follow-list-->
			<div class="follow-list">
				<div class="list">
					<dl>
						<dt><img src="../assets/img/techer_21.jpg"/></dt>
						<dd>
							<h3>朱小刚</h3>
							<p>教育专家，高考桥第一明星</p>
						</dd>
						<dd>
							<button>已关注</button>
						</dd>
					</dl>
					<dl>
						<dt><img src="../assets/img/techer_21.jpg"/></dt>
						<dd>
							<h3>朱小刚</h3>
							<p>教育专家，高考桥第一明星</p>
						</dd>
						<dd>
							<button>已关注</button>
						</dd>
					</dl>
					<dl>
						<dt><img src="../assets/img/techer_21.jpg"/></dt>
						<dd>
							<h3>朱小刚</h3>
							<p>教育专家，高考桥第一明星</p>
						</dd>
						<dd>
							<button>已关注</button>
						</dd>
					</dl>
				</div>				
			</div>
			
			<!--student-->
			<div class="student">
				<span>大学招生办</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--volunteer-->
			<div class="volunteer">
				<img src="../assets/img/techer_14.jpg"/>
				<p>志愿填报</p>
			</div>
			
			<!--plan-->
			<div class="plan">
				<span>职业规划专家</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--family-->
			<div class="family" id="expert">
				<span>家庭教育专家</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--family-list-->
			<div class="family-list">
				<div class="list-me">
					<dl>
						<dt><img src="../assets/img/techer_21.jpg"/></dt>
						<dd>
							<h3>朱小刚</h3>
							<p>教育专家，高考桥第一明星</p>
							<span>明星导师</span><span>签约导师</span><span>志愿专家</span><span>认证导师</span>
						</dd>
						<dd>
							<button><img src="../assets/img/techer_24.jpg"/>关注</button>
						</dd>
					</dl>
					<p>
						我从事过20年高中教育，亲自目送过2万多名学生考上大学，本人擅长讲志愿方面的问题。亲自目送过2万多名学生考上大学，本人擅长讲志愿
					</p>
				</div>
				<div class="list-me">
					<dl>
						<dt><img src="../assets/img/techer_21.jpg"/></dt>
						<dd>
							<h3>朱小刚</h3>
							<p>教育专家，高考桥第一明星</p>
							<span>明星导师</span><span>签约导师</span><span>志愿专家</span><span>认证导师</span>
						</dd>
						<dd>
							<button><img src="../assets/img/techer_24.jpg"/>关注</button>
						</dd>
					</dl>
					<p>
						我从事过20年高中教育，亲自目送过2万多名学生考上大学，本人擅长讲志愿方面的问题。亲自目送过2万多名学生考上大学，本人擅长讲志愿
					</p>
				</div>
				<div class="click">
					<button>点击加载更多<img src="../assets/img/techer_18.jpg" alt="" /></button>
				</div>
			</div>
			
			<!--plan-->
			<div class="plan">
				<span>职业规划专家</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--特定导师-->
			<div class="volunteer">
				<img src="../assets/img/techer_14.jpg"/>
				<p>特定导师</p>
			</div>
			
			<!--plan-->
			<div class="plan">
				<span>职业规划专家</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--family-->
			<div class="family">
				<span>家庭教育专家</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--职业方向-->
			<div class="volunteer">
				<img src="../assets/img/techer_14.jpg"/>
				<p>职业方向</p>
			</div>
			
			<!--plan-->
			<div class="plan">
				<span>职业规划专家</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
			<!--family-->
			<div class="family">
				<span>家庭教育专家</span>
				<img src="../assets/img/techer_11.jpg"/>
			</div>
			
		</div>
		
	</div>
</template>
<script>
	export default{
		methods:{
			show(){}
		}
	}
</script>


