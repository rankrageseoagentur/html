		<script type="text/javascript">
				jQuery(document).ready(function(){
					jQuery("#trial-headbanner-close").click(function(){
						jQuery("#trial-headbanner").animate({height: "0px"},function(){
							jQuery("#trial-headbanner").remove();
						})
						gjAjax.getRequest("/ajax/setData", {type: "user", key: "trialHeadBannerClosed", value: "true"});
					});
				});
			</script>
				
				<style>
			#curationBlock.curationBlockMarginTop {
				top: 151px;
			}
		</style>
		
	</div>
<div id="headbanner"   >
	 			 
<script type="text/javascript">
    function newScoopOnClickAfterPopup() {
        do_newScoopOnClick()
    }
    function do_newScoopOnClick() {
                                    showPost({
                    url: '/t/seo-1325/p/create/2'
                });
                        }
</script>

	<div id="head">
	    	    		    					<div class="headSection head-section-logo">
					<div id="logoToHome"   onclick="trackClick('topBannerLogo', function() {window.location = 'https://www.rankrage.de';})"  ></div>
				</div>
						 				<div class="headSection" id="read-publish-nav">
		            <ul>
		                <li >
		                    <a href="/">READ</a>
		                </li>
		                <li data-dropdown="#publishDropDrown" data-dropdown-top="51"  class="nav-menu-selected" >
		                    <a class="dropdownArrow">PUBLISH</a>
		                </li>
		            </ul>
		        </div>
	                <ul class="dropdown-menu has-tip anchor-left has-icons" id="publishDropDrown">
				    <li>
		        <a onclick="return trackOnClick(this,'topicFromMyTopicsListOnDashboard')" href="/t/online-marketing-by-rankrageseo" title="Online Marketing" class="tooltip-bottom-left " >
		            <img src="https://www.scoop.it/resources/img/V4/theme/noimage-3.png" />
		            
		            <span class="curated-topics-list-name">
		                Online Marketing
		            </span>
		            <span id="curated-topics-list-nb-posts-6579711">
		               
		            </span>
		        </a>
		    </li>
		    <script type="text/javascript">
		        function insertSuggestionsCount(id){
		            gjAjax.postRequest("/ajax/dashboard/myTopicBoxGetNbSuggestions", { themeLid: id},function(){});
		        }
		        jQuery(document).ready(function(){
                    insertSuggestionsCount(6579711);
		        });
		    </script>
				    <li>
		        <a onclick="return trackOnClick(this,'topicFromMyTopicsListOnDashboard')" href="/t/seo-1325" title="SEO (Suchmaschinenoptimierung)" class="tooltip-bottom-left " >
		            <img src="https://img.scoop.it/RbMEqiGiI5eJQvPBwX4iZgviTmyHY4Jvxuq4ekGIxH8=" />
		            
		            <span class="curated-topics-list-name">
		                SEO (Suchmaschinenoptimierung)
		            </span>
		            <span id="curated-topics-list-nb-posts-6582936">
		               
		            </span>
		        </a>
		    </li>
		    <script type="text/javascript">
		        function insertSuggestionsCount(id){
		            gjAjax.postRequest("/ajax/dashboard/myTopicBoxGetNbSuggestions", { themeLid: id},function(){});
		        }
		        jQuery(document).ready(function(){
                    insertSuggestionsCount(6582936);
		        });
		    </script>
				    <li>
		        <a onclick="return trackOnClick(this,'topicFromMyTopicsListOnDashboard')" href="/t/webdesign-by-rankrageseo" title="Webdesign" class="tooltip-bottom-left " >
		            <img src="https://www.scoop.it/resources/img/V4/theme/noimage-3.png" />
		            
		            <span class="curated-topics-list-name">
		                Webdesign
		            </span>
		            <span id="curated-topics-list-nb-posts-6582951">
		               
		            </span>
		        </a>
		    </li>
		    <script type="text/javascript">
		        function insertSuggestionsCount(id){
		            gjAjax.postRequest("/ajax/dashboard/myTopicBoxGetNbSuggestions", { themeLid: id},function(){});
		        }
		        jQuery(document).ready(function(){
                    insertSuggestionsCount(6582951);
		        });
		    </script>
						    <li id="createATopic" class="no-border">
		        <a id="create-a-topic-link-dd" class="button button-blue" href="/theme/create?cc=UserDropdownMenu" onclick="trackClick('clickOnCreateATopicInDropdownUserMenu', null); return true;">
		            Create a Topic
		        </a>
		    </li>
		    		
