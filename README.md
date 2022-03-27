# miniature-chainsaw
const {   bitcoin: { addresses }, } = mempoolJS();  const address = '1wizSAYSbuyXbt9d8JV8ytm5acqq2TorC';  const addressTxsMempool = await addresses.getAddressTxsMempool({ address }); console.log(addressTxsMempool);
