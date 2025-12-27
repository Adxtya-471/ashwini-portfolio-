import streamlit as st
from datetime import datetime

# Page config
st.set_page_config(
    page_title="Ashwini Kumar - Project Manager",
    page_icon="👨‍💼",
    layout="wide",
    initial_sidebar_state="collapsed"
)

# Custom CSS
st.markdown("""
<style>
    .main-header {
        font-size: 4rem !important;
        font-weight: 300 !important;
        text-align: center;
        margin-bottom: 1rem !important;
        color: white !important;
    }
    .subtitle {
        font-size: 1.5rem !important;
        text-align: center;
        opacity: 0.9;
        color: white !important;
    }
    .hero-details {
        font-size: 1.1rem !important;
        text-align: center;
        color: white !important;
    }
    .section-title {
        font-size: 2.5rem !important;
        text-align: center;
        margin-bottom: 2rem !important;
        color: #1a1a1a !important;
    }
    .family-card {
        background: white;
        padding: 2rem;
        border-radius: 12px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        text-align: center;
        height: 100%;
    }
    .family-role {
        color: #007bff !important;
        margin-bottom: 1rem !important;
    }
    .contact-btn {
        padding: 12px 24px !important;
        background: #007bff !important;
        color: white !important;
        border: none !important;
        border-radius: 50px !important;
        font-weight: 500 !important;
        margin: 0 1rem !important;
        text-decoration: none !important;
    }
    .contact-btn:hover {
        background: #0056b3 !important;
        transform: translateY(-2px) !important;
    }
</style>
""", unsafe_allow_html=True)

# Header
st.markdown("""
<div style='background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 4rem 2rem; color: white; text-align: center;'>
    <h1 class='main-header'>Ashwini Kumar</h1>
    <p class='subtitle'>Project Manager at Avalara, Pune</p>
    <div class='hero-details'>
        <span>🕐 Age: 26 | DOB: 10 Feb 1999</span><br>
        <span>👤 Fair Complexion | 📏 5'10" Height</span>
    </div>
</div>
""", unsafe_allow_html=True)

# Navigation
tab1, tab2, tab3, tab4 = st.tabs(["👨‍💼 About", "👨‍👩‍👦 Family", "📞 Contact", "ℹ️ Info"])

with tab1:
    st.markdown('<h2 class="section-title">Professional Background</h2>', unsafe_allow_html=True)
    col1, col2 = st.columns([2, 1])
    with col1:
        st.markdown("""
        **Project Manager at Avalara, Pune** specializing in:
        
        - Team coordination & project planning
        - Stakeholder communication
        - Timely delivery of high-quality projects
        - Aligning business requirements with technical teams
        
        Focused on efficient execution across different domains.
        """)
    with col2:
        st.markdown("""
        **Quick Stats:**
        - **Age:** 26 years
        - **Location:** Pune
        - **DOB:** 10 Feb 1999
        - **Height:** 5 ft 10 in
        - **Complexion:** Fair
        """)

with tab2:
    st.markdown('<h2 class="section-title">Family</h2>', unsafe_allow_html=True)
    col1, col2, col3 = st.columns(3)
    
    with col1:
        st.markdown("""
        <div class="family-card">
            <h3 class="family-role">👨‍✈️ Father</h3>
            <p><strong>Ramesh Mahto</strong><br>
            A.O (Account Officer)<br>
            AG Office, Raipur<br>
            <em>Ex-Sergeant, Indian Air Force (IAF)</em></p>
        </div>
        """, unsafe_allow_html=True)
    
    with col2:
        st.markdown("""
        <div class="family-card">
            <h3 class="family-role">👩 Mother</h3>
            <p><strong>Aarti Mahto</strong><br>
            <em>Homemaker</em></p>
        </div>
        """, unsafe_allow_html=True)
    
    with col3:
        st.markdown("""
        <div class="family-card">
            <h3 class="family-role">🤖 Sibling</h3>
            <p><strong>Aman Kumar</strong><br>
            AI Engineer<br>
            Miko, Mumbai</p>
        </div>
        """, unsafe_allow_html=True)

with tab3:
    st.markdown('<h2 class="section-title">Get in Touch</h2>', unsafe_allow_html=True)
    st.markdown("<p style='text-align: center; font-size: 1.2rem; color: #666;'>Based in Pune | Open to professional connections</p>", unsafe_allow_html=True)
    
    col1, col2, col3 = st.columns([1, 2, 1])
    with col2:
        st.markdown("""
        <div style='text-align: center; margin-top: 2rem;'>
            <a href='mailto:your.email@example.com' class='contact-btn' target='_blank'>📧 Email</a>
            <a href='https://linkedin.com/in/yourprofile' class='contact-btn' target='_blank'>💼 LinkedIn</a>
        </div>
        """, unsafe_allow_html=True)
    
    st.markdown("---")
    with st.expander("📱 Add your contact details here"):
        email = st.text_input("Email")
        phone = st.text_input("Phone")
        linkedin = st.text_input("LinkedIn URL")
        st.info("Update these fields and the buttons will use your info!")

with tab4:
    st.markdown('<h2 class="section-title">Deployment Info</h2>', unsafe_allow_html=True)
    
    st.subheader("🚀 Quick Start")
    st.code("""
    pip install streamlit
    streamlit run app.py
    """)
    
    st.subheader("☁️ Free Hosting - Streamlit Cloud")
    steps = [
        "1. Push code to GitHub repo",
        "2. Go to share.streamlit.io",
        "3. Connect GitHub → Deploy",
        "4. Live URL in 2 minutes!"
    ]
    for step in steps:
        st.write(step)
    
    st.subheader("📱 Features")
    col1, col2 = st.columns(2)
    with col1:
        st.success("✅ Fully responsive")
        st.success("✅ No database needed")
        st.success("✅ Instant updates")
    with col2:
        st.success("✅ Free hosting")
        st.success("✅ Custom domains")
        st.success("✅ Tabs navigation")

# Footer
st.markdown("---")
st.markdown("""
<div style='text-align: center; padding: 2rem; background: #1a1a1a; color: white; margin-top: 3rem;'>
    <p>&copy; {} Ashwini Kumar. All rights reserved. | Built with Streamlit</p>
</div>
""".format(datetime.now().year), unsafe_allow_html=True)
