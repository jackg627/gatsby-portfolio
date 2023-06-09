---
---

<form name="contact" method="POST" data-netlify="true" data-netlify-honeypot="bot-field" style={{ maxWidth: '400px', margin: '0' }}>
 <input type="hidden" name="form-name" value="contact" />
  <div style={{ marginBottom: '1rem' }}>
    <label htmlFor="name" style={{ display: 'block', marginBottom: '0.5rem', fontSize: '1.2rem', fontWeight: 'bold' }}>
      Name:
    </label>
    <input type="text" name="name" required style={{ width: '100%', padding: '0.5rem', backgroundColor: 'lightgrey' }} />
  </div>
  <div style={{ marginBottom: '1rem' }}>
    <label htmlFor="email" style={{ display: 'block', marginBottom: '0.5rem', fontSize: '1.2rem', fontWeight: 'bold' }}>
      Email:
    </label>
    <input type="email" name="email" required style={{ width: '100%', padding: '0.5rem', backgroundColor: 'lightgrey' }} />
  </div>
  <div style={{ marginBottom: '1rem' }}>
    <label htmlFor="message" style={{ display: 'block', marginBottom: '0.5rem', fontSize: '1.2rem', fontWeight: 'bold' }}>
      Message:
    </label>
    <textarea name="message" required style={{ width: '100%', padding: '0.5rem', backgroundColor: 'lightgrey', minHeight: '100px' }} />
  </div>
  <button type="submit" style={{ background: '#f3ab54', color: 'white', padding: '0.5rem 1rem', border: 'none', borderRadius: '4px', fontSize: '1.2rem' }}>
    Send
  </button>
</form>
