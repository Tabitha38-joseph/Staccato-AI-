<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Staccato Salesforce AI Demo</title>
    <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        body { background-color: #b0c4de; font-family: 'Salesforce Sans', Arial, sans-serif; }
        .slds-card { background: white; border: 1px solid #dddbda; border-radius: 0.25rem; }
        .slds-input-label { color: #444; font-size: 0.75rem; margin-bottom: 2px; }
        .slds-value { font-size: 0.875rem; border-bottom: 1px solid #f3f3f2; padding-bottom: 2px; color: #181818; }
        .spinner { animation: rotate 1s linear infinite; width: 24px; height: 24px; border: 3px solid #e0e5ee; border-top-color: #0176d3; border-radius: 50%; }
        @keyframes rotate { 100% { transform: rotate(360deg); } }
        .active-tab { border-bottom: 3px solid #0176d3; color: #0176d3; font-weight: bold; }
    </style>
</head>
<body>
    <div id="root"></div>

    <script type="text/babel">
        const { useState } = React;

        const StaccatoDemo = () => {
            const [loading, setLoading] = useState(false);
            const [showInsights, setShowInsights] = useState(false);

            const runAI = () => {
                setLoading(true);
                setShowInsights(false);
                setTimeout(() => { setLoading(false); setShowInsights(true); }, 2200);
            };

            return (
                <div className="min-h-screen">
                    {/* Salesforce Top Bar */}
                    <div className="bg-[#1b2532] text-white p-2 flex items-center gap-4 text-xs">
                        <div className="font-bold border-r pr-4 border-gray-600">SERVICE CLOUD</div>
                        <div className="opacity-80">Contacts > Babette Staccato</div>
                    </div>

                    <div className="p-4 grid grid-cols-12 gap-4">
                        {/* LEFT COLUMN: Main Record Data */}
                        <div className="col-span-8">
                            <div className="slds-card bg-white min-h-[800px]">
                                <div className="flex border-b text-sm">
                                    <div className="px-6 py-3 active-tab cursor-pointer uppercase tracking-widest text-xs font-bold">Details</div>
                                    <div className="px-6 py-3 text-gray-500 cursor-pointer uppercase tracking-widest text-xs font-bold">Related</div>
                                </div>
                                
                                <div className="p-6">
                                    <h3 className="text-sm font-bold bg-gray-100 p-2 mb-4">Contact Information</h3>
                                    <div className="grid grid-cols-2 gap-x-12 gap-y-6 mb-8">
                                        <Field label="VIP Client" value="[X]" />
                                        <Field label="VIP Type" value="Founding Member" />
                                        <Field label="Profile Tier" value="Platinum" />
                                        <Field label="Account Name" value="Staccato 2023 Master Database" isLink />
                                        <Field label="Title" value="Studio Executive" />
                                        <Field label="Phone" value="+1 555-010-9988" />
                                        <Field label="Email" value="babette@staccato-demo.com" isLink />
                                        <Field label="Mailing Address" value="United States" />
                                    </div>

                                    <h3 className="text-sm font-bold bg-gray-100 p-2 mb-4">Additional Information</h3>
                                    <div className="grid grid-cols-2 gap-x-12 gap-y-6">
                                        <Field label="Customer Tier" value="Platinum" />
                                        <Field label="Lifetime Spend" value="$124,500.00" />
                                        <Field label="Total Lifetime Value" value="$148,000.00" />
                                        <Field label="Total Cases" value="12" />
                                        <Field label="Team Member" value="Sarah Salesforce" />
                                    </div>
                                </div>
                            </div>
                        </div>

                        {/* RIGHT COLUMN: Sidebar & AI */}
                        <div className="col-span-4 space-y-4">
                            
                            {/* AI INSIGHT COMPONENT */}
                            <div className="slds-card overflow-hidden border-2 border-blue-400 shadow-lg">
                                <div className="bg-gradient-to-r from-blue-700 to-blue-900 p-3 flex justify-between items-center">
                                    <div className="flex items-center gap-2 text-white">
                                        <i className="fas fa-robot"></i>
                                        <span className="font-bold text-sm tracking-wide">STACCATO AI INSIGHTS</span>
                                    </div>
                                    <button onClick={runAI} className="text-[10px] bg-white text-blue-800 px-2 py-1 rounded font-bold hover:bg-blue-50">
                                        REFRESH
                                    </button>
                                </div>

                                <div className="p-5 min-h-[300px]">
                                    {!loading && !showInsights && (
                                        <div className="text-center py-10">
                                            <p className="text-gray-500 text-sm mb-4">Analyze customer behavior and <br/>membership trends.</p>
                                            <button onClick={runAI} className="bg-blue-600 text-white px-6 py-2 rounded text-sm font-bold shadow-md hover:bg-blue-700">
                                                Generate AI Summary
                                            </button>
                                        </div>
                                    )}

                                    {loading && (
                                        <div className="flex flex-col items-center justify-center py-10">
                                            <div className="spinner mb-4"></div>
                                            <p className="text-blue-700 font-bold animate-pulse text-sm">Processing Sales & Case History...</p>
                                        </div>
                                    )}

                                    {showInsights && (
                                        <div className="animate-in slide-in-from-bottom-2 duration-500">
                                            <div className="flex items-center justify-between mb-4 pb-3 border-b">
                                                <div>
                                                    <p className="text-[10px] font-bold text-gray-400 uppercase">Customer Health</p>
                                                    <p className="text-green-600 font-black text-lg">STRONG (96%)</p>
                                                </div>
                                                <div className="text-right">
                                                    <p className="text-[10px] font-bold text-gray-400 uppercase">Retention Risk</p>
                                                    <p className="text-gray-800 font-black text-lg">LOW</p>
                                                </div>
                                            </div>

                                            <div className="space-y-4">
                                                <div>
                                                    <h4 className="text-xs font-bold text-blue-800 uppercase flex items-center gap-2">
                                                        <i className="fas fa-chart-line"></i> Purchase Patterns
                                                    </h4>
                                                    <p className="text-xs text-gray-700 mt-1 leading-relaxed">
                                                        Consistent <strong>Platinum</strong> spend profile. 
                                                        Total spend of <strong>$124,500</strong> is in the top 5% of Staccato owners. 
                                                        Typically purchases accessories 30 days after a major gear order.
                                                    </p>
                                                </div>

                                                <div>
                                                    <h4 className="text-xs font-bold text-blue-800 uppercase flex items-center gap-2">
                                                        <i className="fas fa-headphones"></i> Product Affinity
                                                    </h4>
                                                    <p className="text-xs text-gray-700 mt-1 leading-relaxed">
                                                        High interest in <strong>Analog Systems</strong> and <strong>Premium Services</strong>. 
                                                        Responds 4x faster to "Limited Edition" gear notifications.
                                                    </p>
                                                </div>

                                                <div className="bg-green-50 border-l-4 border-green-500 p-3">
                                                    <h4 className="text-xs font-bold text-green-800 uppercase">Recommended Action</h4>
                                                    <p className="text-xs text-green-900 font-medium mt-1">
                                                        Customer Tier is Platinum, but Membership status is "Cancelled". 
                                                        Offer a <strong>Win-Back Membership discount</strong> tied to their most-viewed product category.
                                                    </p>
                                                </div>
                                            </div>
                                        </div>
                                    )}
                                </div>
                            </div>

                            {/* Sidebar Placeholder */}
                            <div className="slds-card p-4">
                                <div className="text-xs font-bold text-gray-500 uppercase mb-4">Related List Quick Links</div>
                                <div className="grid grid-cols-2 gap-2">
                                    <QuickLink label="Cases" count="12" color="bg-red-500" />
                                    <QuickLink label="Orders" count="24" color="bg-blue-500" />
                                    <QuickLink label="Quotes" count="4" color="bg-yellow-500" />
                                    <QuickLink label="Files" count="1" color="bg-green-500" />
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            );
        };

        const Field = ({ label, value, isLink }) => (
            <div className="flex flex-col">
                <span className="slds-input-label">{label}</span>
                <span className={`slds-value ${isLink ? 'text-blue-600 hover:underline cursor-pointer' : ''}`}>
                    {value}
                </span>
            </div>
        );

        const QuickLink = ({ label, count, color }) => (
            <div className="flex items-center gap-2 p-1 border rounded hover:bg-gray-50 cursor-pointer">
                <div className={`w-2 h-2 rounded-full ${color}`}></div>
                <span className="text-xs text-blue-600">{label} ({count})</span>
            </div>
        );

        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(<StaccatoDemo />);
    </script>
</body>
</html># Staccato-AI-
